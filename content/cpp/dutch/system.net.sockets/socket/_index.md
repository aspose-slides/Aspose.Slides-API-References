---
title: Socket
second_title: Aspose.Slides voor C++ API-referentie
description: De Socket-klasse implementeert de Berkeley-socketsinterface.
type: docs
weight: 53
url: /nl/system.net.sockets/socket/
---
## Socket-klasse


De [Socket](./) class implements the Berkeley sockets interface.

```cpp
class Socket : public System::IDisposable
```

## Methoden

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | Maakt een nieuwe socket aan voor de nieuw aangemaakte verbinding. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone connectie-operatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone connectie-operatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone connectie-operatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone connectie-operatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone schrijf-operatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone verzend-operatie. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Bindt de socket aan het opgegeven lokale eindpunt. |
| void [Close](./close/)() | Sluit de socket-verbinding. |
| void [Close](./close/)(int) | Sluit de socket-verbinding met de opgegeven timeout om in de wachtrij staande gegevens te verzenden. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Vestigt een verbinding met het opgegeven externe eindpunt. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Vestigt een verbinding met het opgegeven externe eindpunt. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Vestigt een verbinding met het opgegeven externe eindpunt. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Vestigt een verbinding met het opgegeven externe eindpunt. |
| void [Dispose](./dispose/)() override | Doet niets. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone connectie-operatie voltooid is. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone ontvang-operatie voltooid is. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Wacht tot de opgegeven asynchrone ontvang-operatie voltooid is. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone verzend-operatie voltooid is. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Wacht tot de opgegeven asynchrone verzend-operatie voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Retourneert de adresfamilie. |
| **int32_t** [get_Available](./get_available/)() | Haalt het aantal bytes op dat van het netwerk is ontvangen en beschikbaar is voor lezen. |
| **bool** [get_Blocking](./get_blocking/)() | Haalt een waarde op die aangeeft of de socket zich in de blokkerende modus bevindt. |
| **bool** [get_Connected](./get_connected/)() | Retourneert een waarde die aangeeft of de socket met de externe host is verbonden. |
| **bool** [get_DontFragment](./get_dontfragment/)() | Haalt een waarde op die aangeeft of de socket IP-datagrammen toestaat te fragmenteren. |
| **bool** [get_DualMode](./get_dualmode/)() | Haalt een waarde op die aangeeft of de socket zich in de dual-modus bevindt. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | Haalt een waarde op die aangeeft of de socket broadcast-pakketten toestaat. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Haalt een waarde op die aangeeft of slechts één proces de socket aan een poort kan binden. |
| **bool** [get_IsBound](./get_isbound/)() | Retourneert een waarde die aangeeft of de socket aan een specifieke lokale poort is gebonden. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Haalt een waarde op die aangeeft of de socket het sluiten zal uitstellen om alle in de wacht staande gegevens te verzenden. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | Retourneert het lokale eindpunt. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | Haalt een waarde op die aangeeft of de socket uitgaande multicast-pakketten ontvangt. |
| **bool** [get_NoDelay](./get_nodelay/)() | Haalt een waarde op die aangeeft of de socket het Nagle-algoritme gebruikt. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | Retourneert een waarde die aangeeft of het besturingssysteem en netwerkaanzichten IPv4 ondersteunen. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | Retourneert een waarde die aangeeft of het besturingssysteem en netwerkaanzichten IPv6 ondersteunen. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | Retourneert het protocoltype. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Haalt de grootte van de ontvangbuffer op. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Haalt een periode op waarna een 'Receive'-aanroep zal verlopen. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | Retourneert het externe eindpunt. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Haalt de grootte van de verzendbuffer op. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Haalt een periode op waarna een 'Send'-aanroep zal verlopen. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | Retourneert het sockettype. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | Retourneert een waarde die aangeeft of de huidige host IPv4 ondersteunt. |
| **int16_t** [get_Ttl](./get_ttl/)() | Haalt de TTL-waarde op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die met het object geassocieerd is. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt hashen van aangepaste objecten mogelijk. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Retourneert een pointer naar de implementatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | Retourneert de waarde die overeenkomt met de opgegeven optienaam. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Haalt de waarde op die overeenkomt met de opgegeven optienaam. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Retourneert de waarde die overeenkomt met de opgegeven optienaam. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge aan C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Stelt laag-niveau operationele modi voor de socket in. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Stelt laag-niveau operationele modi voor de socket in. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge aan C# 'is' operator. |
| void [Listen](./listen/)(**int32_t**) | Wijzigt de socket-status naar 'listen'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge aan C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toekenningsoperator. Kopieert niets echt, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | Retourneert de status van de socket op basis van de opgegeven poll-modus. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-arrays. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-arrays. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-arrays. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Ontvangt gegevens van het gespecificeerde eindpunt en schrijft ze naar de gespecificeerde byte-array. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een value-type object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Verzendt de opgegeven gegevens naar de socket. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Verzendt de opgegeven gegevens naar het opgegeven eindpunt. |
| void [set_Blocking](./set_blocking/)(**bool**) | Stelt een waarde in die aangeeft of de socket zich in de blokkerende modus bevindt. |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | Stelt de verbindings-timeout in. |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | Stelt een waarde in die aangeeft of de socket IP-datagrammen mag fragmenteren. |
| void [set_DualMode](./set_dualmode/)(**bool**) | Stelt een waarde in die aangeeft of de socket zich in de dual-modus bevindt. |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | Stelt een waarde in die aangeeft of de socket broadcast-pakketten toestaat. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Stelt een waarde in die aangeeft of slechts één proces de socket aan een poort kan binden. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Stelt een waarde in die aangeeft of de socket het sluiten vertraagt om alle in-wachtrij-gegevens te verzenden. |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | Stelt een waarde in die aangeeft of de socket uitgaande multicast-pakketten ontvangt. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Stelt een waarde in die aangeeft of de socket het Nagle-algoritme gebruikt. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Stelt de grootte van de ontvangbuffer in. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Stelt een periode in waarna een ‘Receive’-aanroep time-out treedt. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Stelt de grootte van de zendbuffer in. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Stelt een periode in waarna een ‘Send’-aanroep time-out treedt. |
| void [set_Ttl](./set_ttl/)(**int16_t**) | Stelt de TTL-waarde in. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Stelt de opgegeven socket-optie in op de opgegeven waarde. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Stelt de opgegeven socket-optie in op de opgegeven waarde. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | Stelt de opgegeven socket-optie in op de opgegeven waarde. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Stelt de opgegeven socket-optie in op de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in op een weak-pointer (in plaats van shared). Staat toe dat pointers in containers naar weak-modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt de gedeelde referentieteller en geeft deze terug. Mag niet rechtstreeks worden aangeroepen; gebruik smart pointers of ThisProtector. |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | Schakelt de verzend- en ontvang-operaties van de socket uit. |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Construeert een nieuw exemplaar. |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Construeert een nieuw exemplaar. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk aangepaste objecten naar een string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert de C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de weak-referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de weak-referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
| virtual  [~Socket](./~socket/)() | Vernietigt het huidige exemplaar. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ImplPtr](./implptr/) | De socket-implementatie. |
## Zie ook

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)