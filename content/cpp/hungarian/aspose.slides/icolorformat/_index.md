---
title: IColorFormat
second_title: Aspose.Slides C++ API referencia
description: Egy prezentációban használt színt képvisel.
type: docs
weight: 1691
url: /hu/aspose.slides/icolorformat/
---
## IColorFormat osztály


Egy prezentációban használt színt képvisel.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Színformátum másolása a "color"-ból. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual **uint8_t** [get_B](./get_b/)() | Visszaadja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Visszaadja az eredményes színt (az összes színtranszformáció alkalmazásával). Beállítja az RGB színeket és törli az összes színtranszformációt. Olvasás: [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Visszaadja a megadott indexnél alkalmazott színtranszformációs műveletet. Olvasás/írás: [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Visszaadja egy színre alkalmazott színtranszformációk gyűjteményét. Csak olvasható: [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Visszaadja a színdefiníciós módszert. Olvasás: [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Visszaadja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Visszaadja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Visszaadja egy szín piros komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Visszaadja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Visszaadja egy szín árnyalat komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Visszaadja egy szín fényesség komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Visszaadja a szín előbeállítását. Olvasás: [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Visszaadja egy szín piros komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Visszaadja egy szín telítettség komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás: **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Visszaadja a színsémával azonosított színt. Olvasás: [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Visszaadja a rendszer színtáblájával azonosított színt. Olvasás: [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciacsámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsámlálót a megadott értékkel. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Beállítja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Visszaadja az eredményes színt (az összes színtranszformáció alkalmazásával). Beállítja az RGB színeket és törli az összes színtranszformációt. Írás: [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Beállítja a megadott indexen alkalmazott színtranszformációs műveletet. Olvasás/írás: [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Beállítja a színdefiníciós módszert. Írás: [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Beállítja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Beállítja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Beállítja egy szín piros komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Beállítja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Beállítja egy szín árnyalat komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Beállítja egy szín fényesség komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Beállítja a szín előbeállítását. Írás: [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Beállítja egy szín piros komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Beállítja egy szín telítettség komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül van hagyva. Írás: **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Beállítja a színsémával azonosított színt. Írás: [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Beállítja a rendszer színtáblájával azonosított színt. Írás: [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók tárolókban való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Visszaad egy [System::String](../../system/string/)-t, amely a jelenlegi színformátumot képviseli. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IFillParamSource](../ifillparamsource/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)