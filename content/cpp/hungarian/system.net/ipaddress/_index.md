---
title: IPAddress
second_title: Aspose.Slides C++ API Referencia
description: "Képviseli az IP címet. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként funkcióknak történő átadáskor."
type: docs
weight: 326
url: /hu/system.net/ipaddress/
---
## IPAddress osztály

Az IP címet képviseli. Ennek az osztálynak a példányait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként funkciókhoz történő átadáskor.

```cpp
class IPAddress : public System::Object
```

## Metódusok

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Visszaadja a címcsaládot. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Visszaad egy értéket, amely jelzi, hogy a cím IPv4-cím, és le van-e térképezve IPv6 címre. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Visszaad egy értéket, amely jelzi, hogy a cím IPv6 link-local cím-e. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Visszaad egy értéket, amely jelzi, hogy a cím globális IPv6 multicast cím-e. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Visszaad egy értéket, amely jelzi, hogy a cím IPv6 site-local cím-e. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Visszaad egy értéket, amely jelzi, hogy a cím IPv6 Teredo cím-e. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Lekéri az IPv6 cím hatókör-azonosítóját. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Visszaad egy bájttömböt az IP címből. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Visszaad egy mutatót a megvalósításra. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Átalakítja a megadott gazdagép bájtrendet a megfelelő hálózati bájtrendre. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Átalakítja a megadott gazdagép bájtrendet a megfelelő hálózati bájtrendre. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Átalakítja a megadott gazdagép bájtrendet a megfelelő hálózati bájtrendre. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Új példányt hoz létre. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Új példányt hoz létre. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Új példányt hoz létre. |
|  [IPAddress](./ipaddress/)() | Új példányt hoz létre. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példányt képviseli-e. A C# 'is' operátor analógja. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Visszaad egy értéket, amely jelzi, hogy a megadott cím loopback cím-e. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | A címet IPv4 címre képezi le. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | A címet IPv6 címre képezi le. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Átalakítja a megadott hálózati bájtrendet a megfelelő gazdagép bájtrendre. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Átalakítja a megadott hálózati bájtrendet a megfelelő gazdagép bájtrendre. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Átalakítja a megadott hálózati bájtrendet a megfelelő gazdagép bájtrendre. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Átalakít egy megadott karakterláncot a [IPAddress](./) osztály egy példányára. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint összehasonlítja az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Beállítja az IPv6 cím hatókör-azonosítóját. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Beállít egy mutatót a megvalósításra. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók átváltását gyenge módra a konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Megpróbál egy megadott karakterláncot a [IPAddress](./) osztály egy példányára konvertálni. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Field | Description |
| --- | --- |
| static [Any](./any/) | Az IPv4 cím, amely jelzi, hogy a szervernek minden hálózati interfészt hallgatnia kell. |
| static [Broadcast](./broadcast/) | Az IPv4 broadcast cím. |
| static [IPv6Any](./ipv6any/) | Az IPv6 cím, amely jelzi, hogy a szervernek minden hálózati interfészt hallgatnia kell. |
| static [IPv6Loopback](./ipv6loopback/) | Az IPv6 loopback cím. |
| static [IPv6None](./ipv6none/) | Az IPv6 cím, amely jelzi, hogy a szervernek nem kell semmilyen hálózati interfészt hallgatnia. |
| static [Loopback](./loopback/) | Az IPv4 loopback cím. |
| static [None](./none/) | Az IPv4 cím, amely jelzi, hogy a szervernek nem kell semmilyen hálózati interfészt hallgatnia. |

## Typedefok

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | Egy mutató a megvalósítás típusára. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névterület [System::Net](../)
* Könyvtár [Aspose.Slides](../../)