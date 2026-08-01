---
title: IFillFormatEffectiveData
second_title: Aspose.Slides voor C++ API-referentie
description: Onveranderlijk object dat effectieve opvulopmaak-eigenschappen bevat.
type: docs
weight: 2120
url: /nl/aspose.slides/ifillformateffectivedata/
---
## IFillFormatEffectiveData klasse

Onveranderlijk object dat effectieve opvulopmaak-eigenschappen bevat.

```cpp
class IFillFormatEffectiveData : public Aspose::Slides::IFillParamSource
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [Aspose::Slides::FillType](../filltype/) [get_FillType](./get_filltype/)() | Retourneert het type vulling. Alleen-lezen [Slides::FillType](../filltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGradientFormatEffectiveData](../igradientformateffectivedata/)\> [get_GradientFormat](./get_gradientformat/)() | Retourneert het gradientopvulformaat. Alleen-lezen [IGradientFormatEffectiveData](../igradientformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPatternFormatEffectiveData](../ipatternformateffectivedata/)\> [get_PatternFormat](./get_patternformat/)() | Retourneert het patroonopvulformaat. Alleen-lezen [IPatternFormatEffectiveData](../ipatternformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormatEffectiveData](../ipicturefillformateffectivedata/)\> [get_PictureFillFormat](./get_picturefillformat/)() | Retourneert het afbeeldingopvulformaat. Alleen-lezen [IPictureFillFormatEffectiveData](../ipicturefillformateffectivedata/). |
| virtual **bool** [get_RotateWithShape](./get_rotatewithshape/)() | Bepaalt of de vulling moet worden geroteerd met de vorm. Alleen-lezen **bool**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_SolidFillColor](./get_solidfillcolor/)() | Retourneert de vulkleur. Alleen-lezen [System::Drawing::Color](../../system.drawing/color/). |
| virtual [SchemeColor](../schemecolor/) [get_SolidFillSchemeColor](./get_solidfillschemecolor/)() | Haalt de vulkleur op die gedefinieerd is door een kleurenschema. De [SchemeColor::NotDefined](../schemecolor/)-waarde geeft aan dat de [IFillFormatEffectiveData::get_SolidFillColor](./get_solidfillcolor/) geen schema-kleur is. Alleen-lezen [SchemeColor](../schemecolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieer-constructor. Kopieert niets echt, initialiseert alleen nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Opmerkingen

Deze interface wordt samen met de [IFillFormat](../ifillformat/) interface gebruikt om effectieve opmaakwaarden met aangebrachte overerving te retourneren.

## Zie ook

* Klasse [IFillParamSource](../ifillparamsource/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)