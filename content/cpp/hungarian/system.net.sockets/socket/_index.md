---
title: Socket
second_title: Aspose.Slides C++ API referencia
description: A Socket osztály megvalósítja a Berkeley socketek interfészét.
type: docs
weight: 53
url: /hu/system.net.sockets/socket/
---
## Socket osztály


A [Socket](./) osztály megvalósítja a Berkeley socket interfészt.

```cpp
class Socket : public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | Létrehoz egy új socketet a nemrég létrehozott kapcsolathoz. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron csatlakozási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron csatlakozási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron csatlakozási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron csatlakozási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron küldési műveletet. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A socketet a megadott helyi végponthoz köti. |
| void [Close](./close/)() | Bezárja a socket kapcsolatot. |
| void [Close](./close/)(int) | Bezárja a socket kapcsolatot a megadott időkorláttal, hogy a sorba állított adatok elküldhetők legyenek. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | Létrehoz egy kapcsolatot a megadott távoli végponttal. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Létrehoz egy kapcsolatot a megadott távoli végponttal. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Létrehoz egy kapcsolatot a megadott távoli végponttal. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Létrehoz egy kapcsolatot a megadott távoli végponttal. |
| void [Dispose](./dispose/)() override | Nem csinál semmit. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Megvárja, amíg a megadott aszinkron csatlakozási művelet befejeződik. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Megvárja, amíg a megadott aszinkron fogadási művelet befejeződik. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Megvárja, amíg a megadott aszinkron fogadási művelet befejeződik. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Megvárja, amíg a megadott aszinkron küldési művelet befejeződik. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | Megvárja, amíg a megadott aszinkron küldési művelet befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értékhez, így a NaN-hez sem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értékhez, így a NaN-hez sem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Visszaadja a címcsaládot. |
| **int32_t** [get_Available](./get_available/)() | Lekéri a hálózatról fogadott és olvasásra rendelkezésre álló bájtok számát. |
| **bool** [get_Blocking](./get_blocking/)() | Lekéri azt az értéket, amely jelzi, hogy a socket blokkoló módban van-e. |
| **bool** [get_Connected](./get_connected/)() | Visszaad egy értéket, amely jelzi, hogy a socket kapcsolódva van-e a távoli kiszolgálóhoz. |
| **bool** [get_DontFragment](./get_dontfragment/)() | Lekéri azt az értéket, amely jelzi, hogy a socket engedélyezi-e az IP-datagramok töredezését. |
| **bool** [get_DualMode](./get_dualmode/)() | Lekéri azt az értéket, amely jelzi, hogy a socket dual-módban van-e. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | Lekéri azt az értéket, amely jelzi, hogy a socket engedélyezi-e a broadcast csomagokat. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Lekéri azt az értéket, amely jelzi, hogy csak egy folyamat kötheti-e a socketet egy porthoz. |
| **bool** [get_IsBound](./get_isbound/)() | Visszaad egy értéket, amely jelzi, hogy a socket egy konkrét helyi porthoz van-e kötve. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Lekéri azt az értéket, amely jelzi, hogy a socket késlelteti-e a lezárást a függőben lévő adatok elküldésének kísérlete érdekében. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | Visszaadja a helyi végpontot. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | Lekéri azt az értéket, amely jelzi, hogy a socket fogad-e kimenő multicast csomagokat. |
| **bool** [get_NoDelay](./get_nodelay/)() | Lekéri azt az értéket, amely jelzi, hogy a socket a Nagle algoritmust használja-e. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | Visszaad egy értéket, amely jelzi, hogy az operációs rendszer és a hálózati adapterek támogatják-e az IPv4-et. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | Visszaad egy értéket, amely jelzi, hogy az operációs rendszer és a hálózati adapterek támogatják-e az IPv6-ot. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | Visszaadja a protokoll típust. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Lekéri a fogadási puffer méretét. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Lekéri azt az időszakot, amely után a 'Receive' hívás időtúllépést eredményez. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | Visszaadja a távoli végpontot. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Lekéri a küldési puffer méretét. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Lekéri azt az időszakot, amely után a 'Send' hívás időtúllépést eredményez. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | Visszaadja a socket típusát. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | Visszaad egy értéket, amely jelzi, hogy az aktuális gép támogatja-e az IPv4-et. |
| **int16_t** [get_Ttl](./get_ttl/)() | Lekéri a TTL értéket. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Visszaad egy mutatót a megvalósításra. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | Visszaadja az értéket, amely a megadott opció névnek megfelelő. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Lekéri az értéket, amely a megadott opció névnek megfelelő. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Visszaadja az értéket, amely a megadott opció névnek megfelelő. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Beállítja a socket alacsony szintű működési módjait. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Beállítja a socket alacsony szintű működési módjait. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Listen](./listen/)(**int32_t**) | Megváltoztatja a socket állapotát 'listen' állapotra. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() állítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstruktorát. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | Visszaadja a socket állapotát a megadott lekérdezési mód alapján. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Adatot fogad a socketből és a megadott bájt tömbbe írja. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | Adatot fogad a socketből és a megadott bájt tömbökbe írja. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | Adatot fogad a socketből és a megadott bájt tömbökbe írja. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | Adatot fogad a socketből és a megadott bájt tömbökbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Adatot fogad a megadott végpontról és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Adatot fogad a megadott végpontról és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Adatot fogad a megadott végpontról és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Adatot fogad a megadott végpontról és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Adatot fogad a megadott végpontról és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | Az adatot a megadott végpontról fogadja, és a megadott bájt tömbbe írja. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával történő összehasonlítása. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával történő összehasonlítása. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Az értéktípusú objektumot referenciával hasonlítja össze a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | A megadott adatot elküldi a socketnek. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | A megadott adatot elküldi a socketnek. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | A megadott adatot a megadott végpontra küldi el. |
| void [set_Blocking](./set_blocking/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a socket blokkoló módban van-e. |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | Beállítja a kapcsolat időkorlátját. |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a socket engedélyezi-e az IP-datagramok töredezését. |
| void [set_DualMode](./set_dualmode/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a socket kettős módban van-e. |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a socket engedélyezi-e a broadcast csomagokat. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Beállít egy értéket, amely jelzi, hogy csak egy folyamat kötheti a socketet egy porthoz. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Beállít egy értéket, amely jelzi, hogy a socket késlelteti-e a lezárást az összes függő adat elküldésének kísérlete érdekében. |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a socket fogadja-e a kimenő multicast csomagokat. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a socket a Nagle-algoritmust használja-e. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Beállítja a fogadó pufferméretét. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Beállít egy időtartamot, amely után a 'Receive' hívás időkorlátba kerül. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Beállítja a küldő pufferméretét. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Beállít egy időtartamot, amely után a 'Send' hívás időkorlátba kerül. |
| void [set_Ttl](./set_ttl/)(**int16_t**) | Beállítja a TTL értékét. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | Beállítja a megadott socket opciót a megadott értékre. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Beállítja a megadott socket opciót a megadott értékre. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | Beállítja a megadott socket opciót a megadott értékre. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Beállítja a megadott socket opciót a megadott értékre. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (a shared helyett) állítja be. Lehetővé teszi a mutatók cseréjét a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | Letiltja a socket küldési és fogadási műveleteit. |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Új példányt hoz létre. |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | Új példányt hoz létre. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok karakterláncra konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
| virtual  [~Socket](./~socket/)() | Megsemmisíti a jelenlegi példányt. |

## Typedefs

| Typedef | Leírás |
| --- | --- |
| [ImplPtr](./implptr/) | A socket megvalósítása. |

## Lásd még

* Osztály [IDisposable](../../system/idisposable/)
* Névterület [System::Net::Sockets](../)
* Könyvtár [Aspose.Slides](../../)