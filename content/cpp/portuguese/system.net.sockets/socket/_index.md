---
title: Socket
second_title: Referência da API Aspose.Slides para C++
description: A classe Socket implementa a interface de sockets Berkeley.
type: docs
weight: 53
url: /pt/system.net.sockets/socket/
---
## Socket classe

A [Socket](./) classe implementa a interface Berkeley sockets.

```cpp
class Socket : public System::IDisposable
```

## Métodos

| Método | Descrição |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | Cria um novo socket para a conexão recém-criada. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia uma operação de conexão assíncrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia uma operação de conexão assíncrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia uma operação de conexão assíncrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia uma operação de conexão assíncrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia uma operação de escrita assíncrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Inicia uma operação de envio assíncrona. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Associa o socket ao endpoint local especificado. |
| void [Close](./close/)() | Fecha a conexão do socket. |
| void [Close](./close/)(int) | Fecha a conexão do socket com o tempo limite especificado para permitir o envio de dados em fila. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Estabelece uma conexão ao endpoint remoto especificado. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Estabelece uma conexão ao endpoint remoto especificado. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Estabelece uma conexão ao endpoint remoto especificado. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Estabelece uma conexão ao endpoint remoto especificado. |
| void [Dispose](./dispose/)() override | Não faz nada. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de conexão assíncrona especificada seja concluída. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de recepção assíncrona especificada seja concluída. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Aguarda até que a operação de recepção assíncrona especificada seja concluída. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Aguarda até que a operação de envio assíncrona especificada seja concluída. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Aguarda até que a operação de envio assíncrona especificada seja concluída. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Retorna a família de endereços. |
| **int32_t** [get_Available](./get_available/)() | Obtém o número de bytes recebidos da rede e disponíveis para leitura. |
| **bool** [get_Blocking](./get_blocking/)() | Obtém um valor que indica se o socket está no modo bloqueante. |
| **bool** [get_Connected](./get_connected/)() | Retorna um valor que indica se o socket está conectado ao host remoto. |
| **bool** [get_DontFragment](./get_dontfragment/)() | Obtém um valor que indica se o socket permite a fragmentação de datagramas IP. |
| **bool** [get_DualMode](./get_dualmode/)() | Obtém um valor que indica se o socket está no modo dual. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | Obtém um valor que indica se o socket permite pacotes de broadcast. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Obtém um valor que indica se somente um processo pode associar o socket a uma porta. |
| **bool** [get_IsBound](./get_isbound/)() | Retorna um valor que indica se o socket está associado a uma porta local específica. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Obtém um valor que indica se o socket atrasará o fechamento numa tentativa de enviar todos os dados pendentes. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | Retorna o endpoint local. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | Obtém um valor que indica se o socket recebe pacotes multicast de saída. |
| **bool** [get_NoDelay](./get_nodelay/)() | Obtém um valor que indica se o socket está usando o algoritmo de Nagle. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | Retorna um valor que indica se o sistema operacional e os adaptadores de rede suportam IPv4. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | Retorna um valor que indica se o sistema operacional e os adaptadores de rede suportam IPv6. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | Retorna o tipo de protocolo. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Obtém o tamanho do buffer de recepção. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Obtém o período após o qual uma chamada 'Receive' expirará. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | Retorna o endpoint remoto. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Obtém o tamanho do buffer de envio. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Obtém o período após o qual uma chamada 'Send' expirará. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | Retorna o tipo de socket. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | Retorna um valor que indica se o host atual suporta IPv4. |
| **int16_t** [get_Ttl](./get_ttl/)() | Obtém o valor TTL. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Retorna um ponteiro para a implementação. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | Retorna o valor que corresponde ao nome da opção especificada. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtém o valor que corresponde ao nome da opção especificada. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Retorna o valor que corresponde ao nome da opção especificada. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Define modos de operação de baixo nível para o socket. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Define modos de operação de baixo nível para o socket. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Listen](./listen/)(**int32_t**) | Altera o estado do socket para 'listen'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | Retorna o status do socket baseado no modo de sondagem especificado. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Recebe dados do socket e grava no array de bytes especificado. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Recebe dados do socket e grava nos arrays de bytes especificados. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Recebe dados do socket e grava nos arrays de bytes especificados. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Recebe dados do socket e grava nos arrays de bytes especificados. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Recebe dados do endpoint especificado e grava no array de bytes especificado. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Envia os dados especificados para o socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Envia os dados especificados para o socket. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Envia os dados especificados para o endpoint especificado. |
| void [set_Blocking](./set_blocking/)(**bool**) | Define um valor que indica se o socket está no modo bloqueante. |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | Define o tempo limite de conexão. |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | Define um valor que indica se o socket permite que datagramas IP sejam fragmentados. |
| void [set_DualMode](./set_dualmode/)(**bool**) | Define um valor que indica se o socket está no modo duplo. |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | Define um valor que indica se o socket permite pacotes broadcast. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Define um valor que indica se apenas um processo pode associar o socket a uma porta. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Define um valor que indica se o socket atrasará o fechamento na tentativa de enviar todos os dados pendentes. |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | Define um valor que indica se o socket recebe pacotes multicast de saída. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Define um valor que indica se o socket está usando o algoritmo de Nagle. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Define o tamanho do buffer de recepção. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Define um período após o qual uma chamada 'Receive' expirará. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Define o tamanho do buffer de envio. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Define um período após o qual uma chamada 'Send' expirará. |
| void [set_Ttl](./set_ttl/)(**int16_t**) | Define o valor TTL. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Define a opção de socket especificada para o valor especificado. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Define a opção de socket especificada para o valor especificado. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | Define a opção de socket especificada para o valor especificado. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Define a opção de socket especificada para o valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | Desabilita as operações de envio e recepção do socket. |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Constrói uma nova instância. |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Constrói uma nova instância. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
| virtual  [~Socket](./~socket/)() | Destrói a instância atual. |
## Tipos Definidos

| TipoDef | Descrição |
| --- | --- |
| [ImplPtr](./implptr/) | A implementação do socket. |
## Veja Também

* Classe [IDisposable](../../system/idisposable/)
* Espaço de nomes [System::Net::Sockets](../)
* Biblioteca [Aspose.Slides](../../)