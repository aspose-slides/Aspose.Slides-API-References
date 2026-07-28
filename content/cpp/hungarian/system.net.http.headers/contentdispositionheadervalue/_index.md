---
title: ContentDispositionHeaderValue
second_title: Aspose.Slides C++ API hivatkozás
description: "A 'Content-Disposition' fejléc értékét képviseli. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 27
url: /hu/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue osztály

A 'Content-Disposition' fejléc értékét képviseli. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával kell allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Módszerek

| Method | Leírás |
| --- | --- |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Új példányt hoz létre. |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)([String](../../system/string/)) | Új példányt hoz létre. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN egyetlen értékhez sem egyenlő, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN egyetlen értékhez sem egyenlő, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_CreationDate](./get_creationdate/)() | A fájl létrehozási dátumát adja vissza. |
| [String](../../system/string/) [get_DispositionType](./get_dispositiontype/)() | Egy elrendezési típust ad vissza. |
| [String](../../system/string/) [get_FileName](./get_filename/)() | Olyan értéket ad vissza, amely meghatározza, hogyan építsen fel egy fájlnevet az üzenet hasznos adatának tárolásához. Akkor használják, amikor az entitás leválasztott és külön fájlban tárolt. |
| [String](../../system/string/) [get_FileNameStar](./get_filenamestar/)() | Olyan értéket ad vissza, amely meghatározza, hogyan építsen fel fájlneveket az üzenet hasznos adatának tárolásához. Akkor használják, amikor az entitások leválasztottak és külön fájlokban tároltak. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ModificationDate](./get_modificationdate/)() | A fájl módosítási dátumát adja vissza. |
| [String](../../system/string/) [get_Name](./get_name/)() | A tartalomtest egy részének nevét adja vissza. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | A 'Content-Disposition' fejléc paramétergyűjteményét adja vissza. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ReadDate](./get_readdate/)() | A fájl legutóbbi olvasási dátumát adja vissza. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Size](./get_size/)() | Megközelítő fájlméretet ad vissza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz társított referenciaszámláló adatstruktúrát adja vissza. |
| static **int32_t** [GetDispositionTypeLength](./getdispositiontypelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Átalakít egy átadott karakterláncot a megadott indexről a [ContentDispositionHeaderValue](./) osztály egy példányává. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzés, hogy az objektum a targetType által leírt típust képviseli-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi a leszármazottak másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi a leszármazottak másoló konstrukcióját. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Átalakít egy átadott karakterláncot a [ContentDispositionHeaderValue](./) osztály egy példányává. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciaként hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciaként hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_CreationDate](./set_creationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Beállítja a fájl létrehozási dátumát. |
| void [set_DispositionType](./set_dispositiontype/)([String](../../system/string/)) | Beállít egy elrendezési típust. |
| void [set_FileName](./set_filename/)([String](../../system/string/)) | Beállít egy olyan értéket, amely meghatározza, hogyan építsen fel egy fájlnevet az üzenet hasznos adatának tárolásához. Akkor használják, amikor az entitás leválasztott és külön fájlban tárolt. |
| void [set_FileNameStar](./set_filenamestar/)([String](../../system/string/)) | Beállít egy olyan értéket, amely meghatározza, hogyan építsen fel fájlneveket az üzenet hasznos adatának tárolásához. Akkor használják, amikor az entitások leválasztottak és külön fájlokban tároltak. |
| void [set_ModificationDate](./set_modificationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Beállítja a fájl módosítási dátumát. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Beállít egy nevet a tartalomtest egy részének. |
| void [set_ReadDate](./set_readdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Beállítja a dátumot, amikor a fájlt legutóbb olvasták. |
| void [set_Size](./set_size/)([Nullable](../../system/nullable/)\<**int64_t**\>) | Beállít egy megközelítő fájlméretet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonparamétert gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\>\&) | Megpróbálja a átadott karakterláncot a [ContentDispositionHeaderValue](./) osztály egy példányává konvertálni. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [ICloneable](../../system/icloneable/)
* Névtér [System::Net::Http::Headers](../)
* Könyvtár [Aspose.Slides](../../)