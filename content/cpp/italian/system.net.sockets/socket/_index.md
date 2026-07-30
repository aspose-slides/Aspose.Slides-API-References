---
title: Socket
second_title: Riferimento API di Aspose.Slides per C++
description: La classe Socket implementa l'interfaccia Berkeley sockets.
type: docs
weight: 53
url: /it/system.net.sockets/socket/
---
## Classe Socket


La classe [Socket](./) implementa l'interfaccia Berkeley sockets.

```cpp
class Socket : public System::IDisposable
```

## Metodi

| Method | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | Crea un nuovo socket per la connessione appena creata. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di connessione asincrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di connessione asincrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di connessione asincrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di connessione asincrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di scrittura asincrona. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Avvia un'operazione di invio asincrona. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Associa il socket all'endpoint locale specificato. |
| void [Close](./close/)() | Chiude la connessione del socket. |
| void [Close](./close/)(int) | Chiude la connessione del socket con il timeout specificato per consentire l'invio dei dati in coda. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Stabilisce una connessione all'endpoint remoto specificato. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Stabilisce una connessione all'endpoint remoto specificato. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Stabilisce una connessione all'endpoint remoto specificato. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Stabilisce una connessione all'endpoint remoto specificato. |
| void [Dispose](./dispose/)() override | Non fa nulla. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Attende fino al completamento dell'operazione di connect asincrona specificata. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Attende fino al completamento dell'operazione di receive asincrona specificata. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Attende fino al completamento dell'operazione di receive asincrona specificata. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Attende fino al completamento dell'operazione di send asincrona specificata. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Attende fino al completamento dell'operazione di send asincrona specificata. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Restituisce la famiglia di indirizzi. |
| **int32_t** [get_Available](./get_available/)() | Ottiene il numero di byte ricevuti dalla rete e disponibili per la lettura. |
| **bool** [get_Blocking](./get_blocking/)() | Ottiene un valore che indica se il socket è in modalità bloccante. |
| **bool** [get_Connected](./get_connected/)() | Restituisce un valore che indica se il socket è connesso all'host remoto. |
| **bool** [get_DontFragment](./get_dontfragment/)() | Ottiene un valore che indica se il socket consente la frammentazione dei datagrammi IP. |
| **bool** [get_DualMode](./get_dualmode/)() | Ottiene un valore che indica se il socket è in modalità duale. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | Ottiene un valore che indica se il socket consente pacchetti broadcast. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Ottiene un valore che indica se solo un processo può associare il socket a una porta. |
| **bool** [get_IsBound](./get_isbound/)() | Restituisce un valore che indica se il socket è associato a una porta locale specifica. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Ottiene un valore che indica se il socket ritarderà la chiusura nel tentativo di inviare tutti i dati in sospeso. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | Restituisce l'endpoint locale. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | Ottiene un valore che indica se il socket riceve pacchetti multicast in uscita. |
| **bool** [get_NoDelay](./get_nodelay/)() | Ottiene un valore che indica se il socket sta usando l'algoritmo di Nagle. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | Restituisce un valore che indica se il sistema operativo e gli adattatori di rete supportano IPv4. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | Restituisce un valore che indica se il sistema operativo e gli adattatori di rete supportano IPv6. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | Restituisce il tipo di protocollo. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Ottiene la dimensione del buffer di ricezione. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Ottiene un intervallo dopo il quale una chiamata 'Receive' scadrà. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | Restituisce l'endpoint remoto. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Ottiene la dimensione del buffer di invio. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Ottiene un intervallo dopo il quale una chiamata 'Send' scadrà. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | Restituisce il tipo di socket. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | Restituisce un valore che indica se l'host corrente supporta IPv4. |
| **int16_t** [get_Ttl](./get_ttl/)() | Ottiene il valore TTL. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Restituisce un puntatore all'implementazione. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | Restituisce il valore corrispondente al nome dell'opzione specificata. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ottiene il valore corrispondente al nome dell'opzione specificata. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Restituisce il valore corrispondente al nome dell'opzione specificata. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Imposta le modalità operative a basso livello per il socket. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Imposta le modalità operative a basso livello per il socket. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Listen](./listen/)(**int32_t**) | Cambia lo stato del socket in 'listen'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | Restituisce lo stato del socket in base alla modalità di polling specificata. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Riceve dati dal socket e li scrive nell'array di byte specificato. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Riceve dati dal socket e li scrive negli array di byte specificati. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Riceve dati dal socket e li scrive negli array di byte specificati. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Riceve dati dal socket e li scrive negli array di byte specificati. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Riceve dati dall'endpoint specificato e li scrive nell'array di byte specificato. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Invia i dati specificati al socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Invia i dati specificati al socket. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Invia i dati specificati all'endpoint specificato. |
| void [set_Blocking](./set_blocking/)(**bool**) | Imposta un valore che indica se il socket è in modalità bloccante. |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | Imposta il timeout di connessione. |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | Imposta un valore che indica se il socket consente la frammentazione dei datagrammi IP. |
| void [set_DualMode](./set_dualmode/)(**bool**) | Imposta un valore che indica se il socket è in modalità duale. |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | Imposta un valore che indica se il socket consente pacchetti broadcast. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Imposta un valore che indica se solo un processo può associare il socket a una porta. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Imposta un valore che indica se il socket ritarderà la chiusura nel tentativo di inviare tutti i dati in attesa. |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | Imposta un valore che indica se il socket riceve pacchetti multicast in uscita. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Imposta un valore che indica se il socket utilizza l'algoritmo di Nagle. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Imposta la dimensione del buffer di ricezione. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Imposta un intervallo dopo il quale una chiamata 'Receive' scadrà. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Imposta la dimensione del buffer di invio. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Imposta un intervallo dopo il quale una chiamata 'Send' scadrà. |
| void [set_Ttl](./set_ttl/)(**int16_t**) | Imposta il valore TTL. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Imposta l'opzione del socket specificata al valore specificato. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Imposta l'opzione del socket specificata al valore specificato. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | Imposta l'opzione del socket specificata al valore specificato. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Imposta l'opzione del socket specificata al valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | Disabilita le operazioni di invio e ricezione del socket. |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Costruisce una nuova istanza. |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Costruisce una nuova istanza. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
| virtual  [~Socket](./~socket/)() | Distrugge l'istanza corrente. |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [ImplPtr](./implptr/) | L'implementazione del socket. |
## Vedi anche

* Classe [IDisposable](../../system/idisposable/)
* Spazio dei nomi [System::Net::Sockets](../)
* Libreria [Aspose.Slides](../../)