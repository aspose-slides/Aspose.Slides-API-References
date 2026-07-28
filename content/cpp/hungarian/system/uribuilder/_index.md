---
title: UriBuilder
second_title: Aspose.Slides C++ API referenciája
description: "Módszereket biztosít univerzális erőforrás-azonosítók (URI-k) létrehozásához és módosításához. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként történő átadásra a függvényeknek."
type: docs
weight: 1405
url: /hu/system/uribuilder/
---
## UriBuilder osztály

Módszereket biztosít az univerzális erőforrás-azonosítók (URI-k) létrehozásához és módosításához. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../makeobject/) függvény segítségével szabad allokálni. Soha ne hozza létre ennek a típusnak a példányát a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class UriBuilder : public System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Az objektumokat C# [Object.Equals](../object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Kizárólag belső célokra. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | A jelenlegi objektum által létrehozott URI sémáját adja vissza. |
| [SharedPtr](../sharedptr/)\<[Uri](../uri/)\> [get_Uri](./get_uri/)() const | A jelenlegi objektum által létrehozott [Uri](../uri/) objektumot adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Az objektumhoz társított referenciaszámláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentinel objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolós konstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolós konstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlít egy értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) specializáció string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) specializáció stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Port](./set_port/)(int) | Beállítja az URI portszámát. |
| void [set_Scheme](./set_scheme/)(const [String](../string/)\&) | Beállítja a jelenlegi objektum által létrehozott URI sémáját a megadott értékre. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként állítja be (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módba történő váltását. |
| int [SharedCount](../object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékét adja vissza. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](./tostring/)() const override | Visszaadja a jelenlegi objektum által létrehozott URI karakterlánc reprezentációját. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Megvalósítja a C# typeof([System.Object](../object/)) konstrukciót. |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentinel objektumot. |
|  [UriBuilder](./uribuilder/)(const [String](../string/)\&) | Létrehoz egy [UriBuilder](./) objektumot, amely a megadott URI-t reprezentálja. |
|  [UriBuilder](./uribuilder/)(const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\&) | Létrehoz egy [UriBuilder](./) objektumot, amely a megadott URI-t reprezentálja. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../object/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)