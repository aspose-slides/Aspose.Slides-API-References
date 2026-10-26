---
title: XmlPreloadedResolver
second_title: Aspose.Slides C++ API-referencia
description: Olyan osztályt képvisel, amely a gyorsítótár előtöltésére használható DTD-kkel vagy XML adatfolyamokkal.
type: docs
weight: 1
url: /hu/system.xml.resolvers/xmlpreloadedresolver/
---
## XmlPreloadedResolver osztály


Olyan osztályt képvisel, amely a gyorsítótár előtöltésére használható DTD-kkel vagy XML adatfolyamokkal.

```cpp
class XmlPreloadedResolver : public System::Xml::XmlResolver
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Hozzáad egy bájt tömböt a [XmlPreloadedResolver](./) tárolóhoz, és egy URI-hez rendeli. Ha a tároló már tartalmaz leképezést ugyanarra az URI-ra, a meglévő leképezés felül lesz írva. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Hozzáad egy bájt tömböt a [XmlPreloadedResolver](./) tárolóhoz, és egy URI-hez rendeli. Ha a tároló már tartalmaz leképezést ugyanarra az URI-ra, a meglévő leképezés felül lesz írva. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Hozzáad egy adatfolyamot a [XmlPreloadedResolver](./) tárolóhoz, és egy URI-hez rendeli. Ha a tároló már tartalmaz leképezést ugyanarra az URI-ra, a meglévő leképezés felül lesz írva. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [String](../../system/string/)\&) | Hozzáad egy előtöltött adatokat tartalmazó karakterláncot a [XmlPreloadedResolver](./) tárolóhoz, és egy URI-hez rendeli. Ha a tároló már tartalmaz leképezést ugyanarra az URI-ra, a meglévő leképezés felül lesz írva. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\>\> [get_PreloadedUris](./get_preloadeduris/)() | Visszaad egy előtöltött URI-k gyűjteményét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetEntity](./getentity/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), const [TypeInfo](../../system/typeinfo/)\&) override | Egy URI-t egy olyan objektumhoz rendel, amely a tényleges erőforrást tartalmazza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az érték típusú objektumot a nullptr-tél. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | Eltávolítja a [XmlPreloadedResolver](./)-ból az URI-hez tartozó adatot. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [ResolveUri](./resolveuri/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) override | Megoldja a teljes URI-t az alap- és relatív URI-kból. |
| void [set_Credentials](./set_credentials/)([SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) override | Beállítja az az alap [Net::WebRequest](../../system.net/webrequest/) hitelesítéséhez használt hitelesítő adatokat. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók tárolókban való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| **bool** [SupportsType](./supportstype/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, const [TypeInfo](../../system/typeinfo/)\&) override | Megállapítja, hogy a resolver támogat-e más típusokat, mint csak a Stream. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)() | Inicializál egy új példányt a [XmlPreloadedResolver](./) osztályból. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)([XmlKnownDtds](../xmlknowndtds/)) | Inicializál egy új példányt a [XmlPreloadedResolver](./) osztályból a megadott előtöltött, jól ismert DTD-kkel. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Inicializál egy új példányt a [XmlPreloadedResolver](./) osztályból a megadott tartalék resolverrel. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&, [XmlKnownDtds](../xmlknowndtds/)) | Inicializál egy új példányt a [XmlPreloadedResolver](./) osztályból a megadott tartalék resolverrel és előtöltött, jól ismert DTD-kkel. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&, [XmlKnownDtds](../xmlknowndtds/), const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\>\>\&) | Inicializál egy új példányt a [XmlPreloadedResolver](./) osztályból a megadott tartalék resolverrel, előtöltött, jól ismert DTD-kkel és URI egyenlőség összehasonlítóval. |
| virtual  [~Object](../../system/object/~object/)() | Nincsont teszi az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutatóra, amely az osztály egy példányára mutat. |

## Megjegyzések

Az osztály példányait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányokat a veremben vagy a new operátorral, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvényeknek argumentumként történő átadásához. 

## Lásd még

* Osztály [XmlResolver](../../system.xml/xmlresolver/)
* Névterület [System::Xml::Resolvers](../)
* Könyvtár [Aspose.Slides](../../)