# jgroups-taller
Configuración de JGroups:

Se utiliza JGroups para manejar la comunicación entre nodos (instancias del chat en diferentes máquinas o procesos).
Configura un canal de comunicación para que cada nodo se conecte a una red común donde pueda enviar y recibir mensajes.
Implementación del canal de chat:

Se crea una instancia del canal y se conecta a un clúster. Este clúster permite que cada nodo comparta mensajes con otros nodos en el mismo canal.
Los mensajes enviados se propagan a todos los nodos conectados al canal.
Envío y recepción de mensajes:

Cada nodo puede enviar un mensaje de texto, que se transmite a través del canal a todos los demás nodos conectados.
Los nodos reciben los mensajes de otros participantes y los muestran en su consola o interfaz.
Eventos de membresía:

JGroups también notifica cuando nuevos nodos se unen o salen del clúster, lo que permite gestionar eventos como la llegada de nuevos usuarios o la desconexión de otros.

Para la ejecución ru file sobre la clase y luego nuevamente para otra instancia, lo que escriba en elas dos si abro una tercera vera todo el historico.