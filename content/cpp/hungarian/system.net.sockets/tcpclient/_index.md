---
title: TcpClient
second_title: Aspose.Slides C++ API referencia
description: "TCP hálózati szolgáltatásokhoz egy klienst reprezentál. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével kell lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 66
url: /hu/system.net.sockets/tcpclient/
---
## TcpClient osztály

A TCP hálózati szolgáltatásokhoz egy klienst reprezentál. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class TcpClient : public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron csatlakozási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron csatlakozási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Elindít egy aszinkron csatlakozási műveletet. |
| void [Close](./close/)() | Bezárja a kapcsolatot és felszabadítja a jelenlegi példányt. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Létrehoz egy kapcsolatot a megadott távoli géppel. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Létrehoz egy kapcsolatot a megadott távoli géppel. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Létrehoz egy kapcsolatot a megadott távoli géppel. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Létrehoz egy kapcsolatot a megadott távoli géppel. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Nem csinál semmit. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Várakozik, amíg a megadott aszinkron csatlakozási művelet be nem fejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN egyetlen értékkel sem egyenlő, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN egyetlen értékkel sem egyenlő, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **int32_t** [get_Available](./get_available/)() | Visszaadja a beérkezett és olvasásra készen álló bájtok számát. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Lekéri a socketet. |
| **bool** [get_Connected](./get_connected/)() | Visszaad egy értéket, amely jelzi, hogy a socket csatlakoztatva van-e a távoli géphez. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Lekéri azt az értéket, amely jelzi, hogy a jelenlegi példány csak egy kliensnek engedélyezi a port használatát. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Lekéri azt az értéket, amely jelzi, hogy a socket késlelteti-e a bezárást a függőben lévő adatok küldésének megkísérlése érdekében. |
| **bool** [get_NoDelay](./get_nodelay/)() | Lekéri azt az értéket, amely jelzi, hogy a jelenlegi példány a Nagle-algoritmust használja-e. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Lekéri a fogadási adatokhoz használt puffer méretét. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Lekéri azt az értéket, amely megadja, hogy mennyi idő után időtúllépés következik az adatok fogadása esetén. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Lekéri a küldési adatokhoz használt puffer méretét. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Lekéri azt az értéket, amely megadja, hogy mennyi idő után időtúllépés következik az adatok küldése esetén. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | Visszaadja a küldéshez és fogadáshoz használt adatfolyamot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít egy értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Beállítja a socketet. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a jelenlegi példány csak egy kliensnek engedélyezi a port használatát. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Beállít egy értéket, amely jelzi, hogy a socket késlelteti-e a bezárást a függőben lévő adatok küldésének megkísérlése érdekében. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a jelenlegi példány a Nagle-algoritmust használja-e. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Beállítja a fogadási adatokhoz használt puffer méretét. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Beállít egy értéket, amely megadja, hogy mennyi idő után időtúllépés következik az adatok fogadása esetén. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Beállítja a küldési adatokhoz használt puffer méretét. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Beállít egy értéket, amely megadja, hogy mennyi idő után időtúllépés következik az adatok küldése esetén. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonparamétert gyenge mutatóvá (a megosztott helyett) állítja be. Lehetővé teszi a mutatók konténerekben való weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Új példányt hoz létre. |
|  [TcpClient](./tcpclient/)() | Új példányt hoz létre. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | Új példányt hoz létre. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | Új példányt hoz létre. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
| virtual  [~TcpClient](./~tcpclient/)() | Megsemmisíti a jelenlegi példányt. |

## Lásd még

* Osztály [IDisposable](../../system/idisposable/)
* Névterület [System::Net::Sockets](../)
* Könyvtár [Aspose.Slides](../../)