---
title: "System::Net::Sockets"
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 729
url: /es/system.net.sockets/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Representa la excepción lanzada cuando ocurre un error de socket. Nunca cree instancias de esta clase manualmente. Use la clase SocketException en su lugar. Nunca envuelva las instancias de la clase SocketException en [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Representa la información del paquete. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarla a funciones como argumento. |
| [LingerOption](./lingeroption/) | Especifica si un socket permanecerá conectado después de una llamada a los métodos Close() o Close(). También especifica el periodo que el socket permanecerá conectado si continúa el envío de datos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarla a funciones como argumento. |
| [NetworkStream](./networkstream/) | Proporciona el flujo subyacente de los datos para el acceso a la red. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarla a funciones como argumento. |
| [Socket](./socket/) | La clase [Socket](./socket/) implementa la interfaz de sockets Berkeley. |
| [TcpClient](./tcpclient/) | Representa un cliente para los servicios de red TCP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarla a funciones como argumento. |
| [TcpListener](./tcplistener/) | Representa un oyente para los servicios de red TCP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarla a funciones como argumento. |
| [UdpClient](./udpclient/) | Proporciona servicios de red User Datagram Protocol (UDP). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarla a funciones como argumento. |

## Funciones

| Función | Descripción |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [SocketType](./sockettype/) | Enumera los tipos de socket. |
| [AddressFamily](./addressfamily/) | Enumera las familias de direcciones. |
| [IOControlCode](./iocontrolcode/) | Enumera los códigos de control [IO](../system.io/). |
| [ProtocolFamily](./protocolfamily/) | Enumera las familias de protocolos. |
| [ProtocolType](./protocoltype/) | Enumera los tipos de protocolo. |
| [SelectMode](./selectmode/) | Especifica el modo para sondear el estado del socket. |
| [SocketError](./socketerror/) | Enumera los tipos de error de socket. |
| [SocketFlags](./socketflags/) | Proporciona valores constantes para los mensajes de socket. |
| [SocketOptionLevel](./socketoptionlevel/) | Define los niveles de opción de socket para la clase '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Define los nombres de opción de socket para la clase [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Define constantes usadas por el método [Socket.Shutdown](./socket/shutdown/). |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [SocketException](./socketexception/) |  |