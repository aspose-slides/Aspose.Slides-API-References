---
title: "System::Net::Sockets"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 677
url: /system.net.sockets/
---



## Classes

| Class | Description |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Represents the exception thrown when a socket error occurs. Never create instances of this class manually. Use the SocketException class instead. Never wrap the SocketException class instances into [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Represents information about the packet. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [LingerOption](./lingeroption/) | Specifies whether a socket will remain connected after a call to the Close() or Close() methods. It also specifies the period the socket will remain connected if sending of the data continues. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [NetworkStream](./networkstream/) | Provides the underlying stream of the data for the network access. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Socket](./socket/) | The [Socket](./socket/) class implements the Berkeley sockets interface. |
| [TcpClient](./tcpclient/) | Represents a client for the TCP network services. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [TcpListener](./tcplistener/) | Represents a listener for the TCP network services. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [UdpClient](./udpclient/) | Provides User Datagram Protocol (UDP) network services. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Functions

| Function | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
## Enums

| Enum | Description |
| --- | --- |
| [SocketType](./sockettype/) | Enumerates the socket types. |
| [AddressFamily](./addressfamily/) | Enumerates the address families. |
| [IOControlCode](./iocontrolcode/) | Enumerates the [IO](../system.io/) control codes. |
| [ProtocolFamily](./protocolfamily/) | Enumerates the protocol families. |
| [ProtocolType](./protocoltype/) | Enumerates the protocol types. |
| [SelectMode](./selectmode/) | Specifies the mode for polling the status of the socket. |
| [SocketError](./socketerror/) | Enumerates the socket error types. |
| [SocketFlags](./socketflags/) | Provides constant values for the socket messages. |
| [SocketOptionLevel](./socketoptionlevel/) | Defines socket option levels for the '[Socket](./socket/)' class. |
| [SocketOptionName](./socketoptionname/) | Defines socket option names for the [Socket](./socket/) class. |
| [SocketShutdown](./socketshutdown/) | Defines constants used by the [Socket.Shutdown](./socket/shutdown/) method. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SocketException](./socketexception/) |  |
