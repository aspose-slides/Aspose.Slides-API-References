---
title: ColorFormat
second_title: Aspose.Slides C++ API referenciája
description: Egy prezentációban használt színt reprezentál.
type: docs
weight: 339
url: /hu/aspose.slides/colorformat/
---
## ColorFormat osztály

Represents a color used in a presentation.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | A színformátumot a \"color\"-ból másolja. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Ellenőrzi, hogy egyenlő-e a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő egyetlen értékkel sem, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő egyetlen értékkel sem, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **uint8_t** [get_B](./get_b/)() override | Visszaadja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül marad. Olvasás **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Visszaadja az eredményes színt (minden színtranszformáció alkalmazásával). Beállítja az RGB színeket és törli az összes színtranszformációt. Olvasás [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Visszaadja a megadott indexnél alkalmazott színtranszformációs műveletet. Olvasás/írás [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Visszaadja egy színre alkalmazott színtranszformációk gyűjteményét. Csak olvasás [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Visszaadja a színdefiníciós módszert. Olvasás [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Visszaadja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül marad. Olvasás **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Visszaadja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül marad. Olvasás **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Visszaadja egy szín piros komponensét. Minden színtranszformáció figyelmen kívül marad. Olvasás **float**. |
| **uint8_t** [get_G](./get_g/)() override | Visszaadja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül marad. |
| **float** [get_Hue](./get_hue/)() override | Visszaadja egy szín árnyalat komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül marad. Olvasás **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Visszaadja egy szín fényesség komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül marad. Olvasás **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Visszaadja a Parent_Immediate objektumot. Csak olvasás [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/)-t. Csak olvasás [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Visszaadja a szín előre beállított értékét. Olvasás [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Visszaadja egy szín piros komponensét. Minden színtranszformáció figyelmen kívül marad. Olvasás **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Visszaadja egy szín telítettség komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül marad. Olvasás **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Visszaadja a színpaletta által azonosított színt. Olvasás [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Visszaadja a rendszer szín táblája által azonosított színt. Olvasás [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi a másoló konstrukciót az alosztályokban. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi a másoló konstrukciót az alosztályokban. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az érték típusú objektumot a nullptr-bal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) sztring és nullptr esetére való specializációja. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) sztringek esetére való specializációja. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_B](./set_b/)(**uint8_t**) override | Beállítja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül marad. Írás **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Visszaadja az eredményes színt (minden színtranszformáció alkalmazásával). Beállítja az RGB színeket és törli az összes színtranszformációt. Írás [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Beállítja a megadott indexnél alkalmazott színtranszformációs műveletet. Olvasás/írás [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Beállítja a színdefiníciós módszert. Írás [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Beállítja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül marad. Írás **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Beállítja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül marad. Írás **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Beállítja egy szín piros komponensét. Minden színtranszformáció figyelmen kívül marad. Írás **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Beállítja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül marad. |
| void [set_Hue](./set_hue/)(**float**) override | Beállítja egy szín árnyalat komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül marad. Írás **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Beállítja egy szín fényesség komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül marad. Írás **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Beállítja a szín előre beállított értékét. Írás [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Beállítja egy szín piros komponensét. Minden színtranszformáció figyelmen kívül marad. Írás **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Beállítja egy szín telítettség komponensét HSL ábrázolásban. Minden színtranszformáció figyelmen kívül marad. Írás **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Beállítja a színpaletta által azonosított színt. Írás [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Beállítja a rendszer szín táblája által azonosított színt. Írás [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablon argumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Visszaad egy [System::String](../../system/string/) objektumot, amely a jelenlegi színformátumot reprezentálja. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [PVIObject](../pviobject/)
* Osztály [IColorFormat](../icolorformat/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)