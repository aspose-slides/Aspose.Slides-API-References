---
title: ShapeStyle
second_title: Aspose.Slides C++ API referencia
description: A forma stílusreferenciáját képviseli.
type: docs
weight: 5149
url: /hu/aspose.slides/shapestyle/
---
## ShapeStyle osztály

A forma stílusreferenciáját képviseli.

```cpp
class ShapeStyle : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Shape>>,
                   public Aspose::Slides::IShapeStyle
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást utánoz, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékhez, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást utánoz, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékhez, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_EffectColor](./get_effectcolor/)() override | Visszaadja a forma hatás színét. Csak olvasható [IColorFormat](../icolorformat/). |
| **uint32_t** [get_EffectStyleIndex](./get_effectstyleindex/)() override | Visszaadja a forma hatás oszlopszámát egy stílusmátrixban. Olvas **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FillColor](./get_fillcolor/)() override | Visszaadja a forma kitöltés színét. Csak olvasható [IColorFormat](../icolorformat/). |
| **int16_t** [get_FillStyleIndex](./get_fillstyleindex/)() override | Visszaadja a forma kitöltés oszlopszámát a stílusmátrixokban. 0 jelent kitöltés hiányát, pozitív érték – a téma kitöltési stílusainak indexe, negatív érték – a téma háttérstílusainak indexe. Olvas **int16_t**. |
| [Aspose::Slides::FontCollectionIndex](../fontcollectionindex/) [get_FontCollectionIndex](./get_fontcollectionindex/)() override | Visszaadja a forma betűtípus indexét egy betűtípusgyűjteményben. Olvas [Slides::FontCollectionIndex](../fontcollectionindex/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FontColor](./get_fontcolor/)() override | Visszaadja a forma betűszínét. Csak olvasható [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_LineColor](./get_linecolor/)() override | Visszaadja a forma körvonal színét. Csak olvasható [IColorFormat](../icolorformat/). |
| **uint16_t** [get_LineStyleIndex](./get_linestyleindex/)() override | Visszaadja a vonal oszlopszámát egy stílusmátrixban. Olvas **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze egy értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_EffectStyleIndex](./set_effectstyleindex/)(**uint32_t**) override | Beállítja a forma hatás oszlopszámát egy stílusmátrixban. Ír **uint32_t**. |
| void [set_FillStyleIndex](./set_fillstyleindex/)(**int16_t**) override | Beállítja a forma kitöltés oszlopszámát a stílusmátrixokban. 0 jelent kitöltés hiányát, pozitív érték – a téma kitöltési stílusainak indexe, negatív érték – a téma háttérstílusainak indexe. Ír **int16_t**. |
| void [set_FontCollectionIndex](./set_fontcollectionindex/)([Aspose::Slides::FontCollectionIndex](../fontcollectionindex/)) override | Beállítja a forma betűtípus indexét egy betűtípusgyűjteményben. Ír [Slides::FontCollectionIndex](../fontcollectionindex/). |
| void [set_LineStyleIndex](./set_linestyleindex/)(**uint16_t**) override | Beállítja a vonal oszlopszámát egy stílusmátrixban. Ír **uint16_t**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók átváltását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DomObject](../domobject/)
* Osztály [IShapeStyle](../ishapestyle/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)