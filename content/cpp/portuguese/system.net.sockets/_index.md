---
title: "System::Net::Sockets"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 729
url: /pt/system.net.sockets/
---
## Classes

| Class | Description |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Representa a exceção lançada quando ocorre um erro de socket. Nunca crie instâncias desta classe manualmente. Use a classe SocketException em vez disso. Nunca encapsule instâncias da classe SocketException em [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Representa informações sobre o pacote. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [LingerOption](./lingeroption/) | Especifica se um socket permanecerá conectado após uma chamada aos métodos Close() ou Close(). Também especifica o período em que o socket permanecerá conectado se o envio dos dados continuar. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [NetworkStream](./networkstream/) | Fornece o fluxo subjacente dos dados para o acesso à rede. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [Socket](./socket/) | A classe [Socket](./socket/) implementa a interface de sockets Berkeley. |
| [TcpClient](./tcpclient/) | Representa um cliente para os serviços de rede TCP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [TcpListener](./tcplistener/) | Representa um ouvinte para os serviços de rede TCP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [UdpClient](./udpclient/) | Fornece serviços de rede do Protocolo de Datagramas do Usuário (UDP). Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |

## Funções

| Function | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## Enumerações

| Enum | Description |
| --- | --- |
| [SocketType](./sockettype/) | Enumera os tipos de socket. |
| [AddressFamily](./addressfamily/) | Enumera as famílias de endereços. |
| [IOControlCode](./iocontrolcode/) | Enumera os códigos de controle [IO](../system.io/). |
| [ProtocolFamily](./protocolfamily/) | Enumera as famílias de protocolo. |
| [ProtocolType](./protocoltype/) | Enumera os tipos de protocolo. |
| [SelectMode](./selectmode/) | Especifica o modo de sondagem do status do socket. |
| [SocketError](./socketerror/) | Enumera os tipos de erro de socket. |
| [SocketFlags](./socketflags/) | Fornece valores constantes para as mensagens de socket. |
| [SocketOptionLevel](./socketoptionlevel/) | Define os níveis de opção de socket para a classe '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Define os nomes de opção de socket para a classe [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Define constantes usadas pelo método [Socket.Shutdown](./socket/shutdown/). |

## Definições de Tipo

| Typedef | Description |
| --- | --- |
| [SocketException](./socketexception/) |  |