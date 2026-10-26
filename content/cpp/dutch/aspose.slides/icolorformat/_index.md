---
title: IColorFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een kleur voor die in een presentatie wordt gebruikt.
type: docs
weight: 1691
url: /nl/aspose.slides/icolorformat/
---
## IColorFormat klasse


Represents a color used in a presentation.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Methoden

| Method | Description |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Kopieert kleurformaat van "color". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-kommagelijken waar twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-kommagelijken waar twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **uint8_t** [get_B](./get_b/)() | Retourneert het blauwe component van een kleur. Alle kleurovertransformaties worden genegeerd. Lezen **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Retourneert de resulterende kleur (met alle kleurovertransformaties toegepast). Stelt RGB-kleuren in en wist alle kleurovertransformaties. Lezen [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Retourneert de color-transformatie-operatie toegepast op kleur op de opgegeven index. Lezen/Schrijven [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Retourneert de collectie van kleurtransformaties toegepast op een kleur. Alleen-lezen [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Retourneert de kleurdefinitiemethode. Lezen [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Retourneert het blauwe component van een kleur. Alle kleurovertransformaties worden genegeerd. Lezen **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Retourneert het groene component van een kleur. Alle kleurovertransformaties worden genegeerd. Lezen **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Retourneert het rode component van een kleur. Alle kleurovertransformaties worden genegeerd. Lezen **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Retourneert het groene component van een kleur. Alle kleurovertransformaties worden genegeerd. Lezen **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Retourneert het tintcomponent van een kleur in HSL-representatie. Alle kleurovertransformaties worden genegeerd. Lezen **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Retourneert het luminantcomponent van een kleur in HSL-representatie. Alle kleurovertransformaties worden genegeerd. Lezen **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Retourneert de kleurpreset. Lezen [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Retourneert het rode component van een kleur. Alle kleurovertransformaties worden genegeerd. Lezen **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Retourneert het verzadigingscomponent van een kleur in HSL-representatie. Alle kleurovertransformaties worden genegeerd. Lezen **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Retourneert de kleur geïdentificeerd door een kleurenpalet. Lezen [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Retourneert de kleur geïdentificeerd door de systeemtabel voor kleuren. Lezen [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analog van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waakhond-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructeur. Kopieert eigenlijk niets, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Stelt het blauwe component van een kleur in. Alle kleurovertransformaties worden genegeerd. Schrijven **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Retourneert de resulterende kleur (met alle kleurovertransformaties toegepast). Stelt RGB-kleuren in en wist alle kleurovertransformaties. Schrijven [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Stel kleurtransformatie-operatie in die op kleur op de opgegeven index wordt toegepast. Lezen/Schrijven [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Stelt de kleurdefinitiemethode in. Schrijven [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Stelt het blauwe component van een kleur in. Alle kleurovertransformaties worden genegeerd. Schrijven **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Stelt het groene component van een kleur in. Alle kleurovertransformaties worden genegeerd. Schrijven **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Stelt het rode component van een kleur in. Alle kleurovertransformaties worden genegeerd. Schrijven **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Stelt het groene component van een kleur in. Alle kleurovertransformaties worden genegeerd. Schrijven **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Stelt het tintcomponent van een kleur in HSL-representatie in. Alle kleurovertransformaties worden genegeerd. Schrijven **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Stelt het luminantcomponent van een kleur in HSL-representatie in. Alle kleurovertransformaties worden genegeerd. Schrijven **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Stelt de kleurpreset in. Schrijven [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Stelt het rode component van een kleur in. Alle kleurovertransformaties worden genegeerd. Schrijven **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Stelt het verzadigingscomponent van een kleur in HSL-representatie in. Alle kleurovertransformaties worden genegeerd. Schrijven **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Stelt de kleur in die door een kleurenpalet wordt geïdentificeerd. Schrijven [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Stelt de kleur in die door de systeemtabel voor kleuren wordt geïdentificeerd. Schrijven [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Retourneert een [System::String](../../system/string/) die het huidige kleurformaat representeert. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waakhond-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [IFillParamSource](../ifillparamsource/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)