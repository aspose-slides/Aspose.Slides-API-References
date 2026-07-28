---
title: BoxedEnum
second_title: Aspose.Slides for C++ API referencia
description: "Becsomagolt felsoroló értéket képvisel. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásra."
type: docs
weight: 92
url: /hu/system/boxedenum/
---
## BoxedEnum osztály

A becsomagolt felsoroló értéket képviseli. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../smartptr/) mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként való átadásához.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| E | A felsoroló érték típusa |
| UT | Az **E** felsoroló alaptípusa |

## Módszerek

| Módszer | Leírás |
| --- | --- |
|  [BoxedEnum](./boxedenum/)(E) | Létrehozza azt a példányt, amely a megadott felsoroló értéket képviseli. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Megkapja az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| virtual [TypeCode](../typecode/) [GetTypeCode](../boxedvaluebase/gettypecode/)() const | Visszaadja a jelenlegi objektum által képviselt becsomagolt érték típusát jelző értéket. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Átalakítja a becsomagolt felsoroló állandó értékét 64 bites egész számra. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# ’is’ operátor analógja. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Megállapítja, hogy a jelenlegi objektum enum típusú becsomagolt értéket képvisel-e. |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrzőobjektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorának használatát. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadás operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorának használatát. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Becsomagolja a megadott felsoroló adott állandó értékét a megadott névvel. Egy paraméter meghatározza, hogy a kis- és nagybetűk figyelmen kívül legyenek-e hagyva a felsoroló állandó nevét meghatározó karakterlánc értelmezésekor. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Becsomagolja a megadott felsoroló adott állandó értékét a megadott névvel. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Referencia alapján hasonlítja össze az objektumokat. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Referencia alapján hasonlítja össze az objektumokat. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja karakterlánc és nullptr esetén. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja karakterláncok esetén. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (ahelyett, hogy megosztott lenne) állítja be. Lehetővé teszi a mutatók átkapcsolását a gyenge módra a konténerekben. |
| int [SharedCount](../object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [System::String](../string/) [ToString](./tostring/)() const override | Átalakítja a jelenlegi objektum által képviselt becsomagolt értéket karakterlánccá. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | A megadott formátumkarakterlánc használatával alakítja a becsomagolt objektumot karakterlánccá. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Megvalósítja a C# typeof([System.Object](../object/)) konstrukciót. |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [BoxedValue](../boxedvalue/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)