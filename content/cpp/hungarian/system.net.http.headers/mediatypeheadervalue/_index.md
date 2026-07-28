---
title: MediaTypeHeaderValue
second_title: Aspose.Slides for C++ API referencia
description: "A 'Content-Type' fejléc értékeként MIME típust képvisel. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként függvényeknek történő átadásához."
type: docs
weight: 144
url: /hu/system.net.http.headers/mediatypeheadervalue/
---
## MediaTypeHeaderValue osztály

A 'Content-Type' fejléc értékeként egy MIME típust reprezentál. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként függvényeknek történő átadáshoz.

```cpp
class MediaTypeHeaderValue : public virtual System::ICloneable
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utaként működteti a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értékkel, így a NaN-nal sem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utaként működteti a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értékkel, így a NaN-nal sem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [String](../../system/string/) [get_CharSet](./get_charset/)() | Karakterkészletet kap. |
| [String](../../system/string/) [get_MediaType](./get_mediatype/)() | A média-típus fejléc értékét adja vissza. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | A média-típus fejléc értékparamétereit adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz társított referencia számláló adatstruktúrát adja vissza. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| static **int32_t** [GetMediaTypeLength](./getmediatypelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](./)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](./)\>\&) | Átalakít egy megadott karakterláncot a megadott indexről a [MediaTypeHeaderValue](./) osztály egy példányává. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)() | Új példányt hoz létre. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)([String](../../system/string/)) | Új példányt hoz létre. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| static [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Átalakít egy megadott karakterláncot a [MediaTypeHeaderValue](./) osztály egy példányává. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlít össze egy értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja több karakterlánc esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_CharSet](./set_charset/)([String](../../system/string/)) | Beállít egy karakterkészletet. |
| void [set_MediaType](./set_mediatype/)([String](../../system/string/)) | Beállítja a média-típus fejléc értékét. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként állítja be (a megosztott helyett). Lehetővé teszi a mutatók tárolókban történő gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referencia számláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok karakterlánccá alakítását. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](./)\>\&) | Megpróbál egy megadott karakterláncot a [MediaTypeHeaderValue](./) osztály egy példányává konvertálni. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) szerkezetet valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [ICloneable](../../system/icloneable/)
* Névtér [System::Net::Http::Headers](../)
* Könyvtár [Aspose.Slides](../../)