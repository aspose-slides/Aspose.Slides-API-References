---
title: ColorFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een kleur die in een presentatie wordt gebruikt.
type: docs
weight: 339
url: /nl/aspose.slides/colorformat/
---
## ColorFormat klasse


Represents a color used in a presentation.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Kopieer kleurindeling van \"color\". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Controleert op gelijkheid met het opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten volgens C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-punt vergelijking waarbij twee NaN’s als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-punt vergelijking waarbij twee NaN’s als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **uint8_t** [get_B](./get_b/)() override | Geeft het blauwe component van een kleur terug. Alle kleurovergangen worden genegeerd. Lezen **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Geeft de resulterende kleur terug (met alle kleurovergangen toegepast). Stelt RGB-kleuren in en wist alle kleurovergangen. Lezen [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Geeft de kleurovergangsbewerking terug die op de kleur is toegepast op de opgegeven index. Lezen/schrijven [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Geeft de collectie van op een kleur toegepaste kleurovergangen terug. Alleen-lezen [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Geeft de kleurdefinitiemethode terug. Lezen [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Geeft het blauwe component van een kleur terug. Alle kleurovergangen worden genegeerd. Lezen **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Geeft het groene component van een kleur terug. Alle kleurovergangen worden genegeerd. Lezen **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Geeft het rode component van een kleur terug. Alle kleurovergangen worden genegeerd. Lezen **float**. |
| **uint8_t** [get_G](./get_g/)() override | Geeft het groene component van een kleur terug. Alle kleurovergangen worden genegeerd. |
| **float** [get_Hue](./get_hue/)() override | Geeft het tint-component van een kleur in HSL-representatie terug. Alle kleurovergangen worden genegeerd. Lezen **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Geeft het luminantie-component van een kleur in HSL-representatie terug. Alle kleurovergangen worden genegeerd. Lezen **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Geeft Parent_Immediate-object terug. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Geeft bovenliggend [IPresentationComponent](../ipresentationcomponent/) terug. Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Geeft de kleur-preset terug. Lezen [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Geeft het rode component van een kleur terug. Alle kleurovergangen worden genegeerd. Lezen **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Geeft het verzadigings-component van een kleur in HSL-representatie terug. Alle kleurovergangen worden genegeerd. Lezen **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Geeft de kleur terug die wordt geïdentificeerd door een kleurschema. Lezen [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Geeft de kleur terug die wordt geïdentificeerd door de systeemkleurentabel. Lezen [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller-datastructuur op die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Geeft de hash-code terug. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analoge van C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieer-constructor. Kopieert niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentie-telling met de opgegeven waarde. |
| void [set_B](./set_b/)(**uint8_t**) override | Stelt het blauwe component van een kleur in. Alle kleurovergangen worden genegeerd. Schrijf **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Geeft de resulterende kleur terug (met alle kleurovergangen toegepast). Stelt RGB-kleuren in en wist alle kleurovergangen. Schrijf [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Stelt de kleurovergangsbewerking in die op de kleur wordt toegepast op de opgegeven index. Lezen/schrijven [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Stelt de kleurdefinitiemethode in. Schrijf [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Stelt het blauwe component van een kleur in. Alle kleurovergangen worden genegeerd. Schrijf **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Stelt het groene component van een kleur in. Alle kleurovergangen worden genegeerd. Schrijf **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Stelt het rode component van een kleur in. Alle kleurovergangen worden genegeerd. Schrijf **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Stelt het groene component van een kleur in. Alle kleurovergangen worden genegeerd. |
| void [set_Hue](./set_hue/)(**float**) override | Stelt het tint-component van een kleur in HSL-representatie in. Alle kleurovergangen worden genegeerd. Schrijf **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Stelt het luminantie-component van een kleur in HSL-representatie in. Alle kleurovergangen worden genegeerd. Schrijf **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Stelt de kleur-preset in. Schrijf [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Stelt het rode component van een kleur in. Alle kleurovergangen worden genegeerd. Schrijf **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Stelt het verzadigings-component van een kleur in HSL-representatie in. Alle kleurovergangen worden genegeerd. Schrijf **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Stelt de kleur in die wordt geïdentificeerd door een kleurschema. Schrijf [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Stelt de kleur in die wordt geïdentificeerd door de systeemkleurentabel. Schrijf [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentie-telling op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentie-telling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt de gedeelde referentie-telling en retourneert deze. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Geeft een [System::String](../../system/string/) terug die het huidige kleurformaat representeert. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentie-telling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentie-telling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Libereert alle interne datastructuren. |

## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [IColorFormat](../icolorformat/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)