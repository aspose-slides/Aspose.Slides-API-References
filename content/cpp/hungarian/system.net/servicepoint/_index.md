---
title: ServicePoint
second_title: Aspose.Slides C++ API Referencia
description: "HTTP kapcsolatkezelést biztosít. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 417
url: /hu/system.net/servicepoint/
---
## ServicePoint osztály

HTTP kapcsolatkezelést biztosít. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class ServicePoint : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | Bezárja és eltávolítja a megadott kapcsolati csoporthoz tartozó kapcsolatokat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Visszaadja a kiszolgáló URI-t, amelyhez a jelen példány csatlakozik. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | Lekérdezi azt a delegáltat, amely a helyi [IPEndPoint](../ipendpoint/) és a jelen példány összekapcsolására szolgál. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | Visszaad egy tanúsítványt, amelyet a jelen példány használ. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | Visszaadja az utolsó kliens tanúsítványt. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Lekérdezi a miliszekundumban megadott időtúllépést, amely után az aktív [ServicePoint](./) le lesz zárva. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | Lekérdezi a jelen példány által engedélyezett legnagyobb kapcsolatszámot. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | Visszaadja a kapcsolat nevét. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | Visszaadja a nyitott kapcsolatok számát. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | Lekérdezi, hogy a 100-Continue viselkedés használatban van-e. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | Visszaadja a legutóbbi hosthoz létesített kapcsolat dátumát és időpontját. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | Lekérdezi a miliszekundumban megadott időt, amely után egy üresjárati kapcsolat le lesz zárva. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | Visszaadja a HTTP verziót. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Lekérdezi a fogadó puffer méretét. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | Visszaadja, hogy a jelen példány támogatja-e a csővezeték kapcsolatokat. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Lekérdezi, hogy a jelen példány által kezelt kapcsolatok használják-e a Nagle-algoritmust. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolópéldányosítását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolópéldányosítását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot nullptr-tel referencia szerint hasonlít össze. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | Beállítja a delegáltat, amely a helyi [IPEndPoint](../ipendpoint/) és a jelen példány összekapcsolására szolgál. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | Beállítja a miliszekundumban megadott időtúllépést, amely után az aktív [ServicePoint](./) le lesz zárva. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | Beállítja a jelen példány által engedélyezett legnagyobb kapcsolatszámot. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Beállítja, hogy a 100-Continue viselkedés használatban van-e. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | Beállítja a miliszekundumban megadott időt, amely után egy üresjárati kapcsolat le lesz zárva. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Beállítja a fogadó puffer méretét. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Beállítja, hogy a jelen példány által kezelt kapcsolatok használják-e a Nagle-algoritmust. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Beállítja, hogy a 'Keep-Alive' opció engedélyezve van-e. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként (nem megosztott) állítja be. Lehetővé teszi a mutatók átkapcsolását gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok karakterlánccá alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névterület [System::Net](../)
* Könyvtár [Aspose.Slides](../../)