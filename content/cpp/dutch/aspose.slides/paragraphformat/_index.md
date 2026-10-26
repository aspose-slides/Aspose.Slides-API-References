---
title: ParagraphFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Deze klasse bevat de alinea-opmaak-eigenschappen. In tegenstelling tot IParagraphFormatEffectiveData zijn alle eigenschappen van deze klasse beschrijfbaar.
type: docs
weight: 4668
url: /nl/aspose.slides/paragraphformat/
---
## ParagraphFormat klasse


Deze klasse bevat de alinea-opmaak-eigenschappen. In tegenstelling tot [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) zijn alle eigenschappen van deze klasse beschrijfbaar.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met gespecificeerd object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Retourneert de tekstuitlijning in een alinea zonder overerving. Lees [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Retourneert de standaard tabulatiegrootte zonder overerving. Lees **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Retourneert een lettertype-uitlijning in een alinea zonder overerving. Lees [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Bepaalt of de hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Retourneert eerste regelinsprong/hangende insprong van een alinea zonder overerving. Hangende insprong kan worden gedefinieerd met negatieve waarden. Lees **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Retourneert de linkermarge in een alinea zonder overerving. Lees **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Retourneert de rechtermarge in een alinea zonder overerving. Lees **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate-object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert bovenliggend [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Bepaalt of Rechts-naar-Links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Retourneert de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving. Een positieve waarde specificeert het percentage van de lettergrootte dat de witruimte moet zijn. Een negatieve waarde specificeert de grootte van de witruimte in punten. Schrijf **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Retourneert de hoeveelheid ruimte voor de eerste regel in een alinea zonder overerving. Een positieve waarde specificeert het percentage van de lettergrootte dat de witruimte moet zijn. Een negatieve waarde specificeert de grootte van de witruimte in punten. Schrijf **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Retourneert de hoeveelheid ruimte tussen basisregels in een alinea. Positieve waarde betekent percentage, negatieve – grootte in punten. Geen overerving toegepast. Lees **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Retourneert de tabulatie van een alinea op de opgegeven index. Geen overerving toegepast. Alleen-lezen [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Retourneert tabulaties van een alinea. Geen overerving toegepast. Alleen-lezen [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die bij het object hoort. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Haalt effectieve alinea-opmaakgegevens op met de toegebrachte overerving. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert hash-code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waarschuwingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert niets echt, alleen initialiseert nieuw object en maakt kopie-construeren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, alleen initialiseert nieuw object en maakt kopie-construeren van subklassen mogelijk. |
|  [ParagraphFormat](./paragraphformat/)() | Initialiseert een nieuwe instantie van [ParagraphFormat](./) klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie van waarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met opgegeven waarde. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Stelt de tekstuitlijning in een alinea zonder overerving in. Schrijf [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Stelt de standaard tabulatiegrootte in zonder overerving. Schrijf **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Stelt een lettertype-uitlijning in een alinea zonder overerving in. Schrijf [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Bepaalt of de hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Stelt eerste regelinsprong/hangende insprong van een alinea in zonder overerving. Hangende insprong kan met negatieve waarden worden gedefinieerd. Schrijf **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Stelt de linkermarge in een alinea zonder overerving in. Schrijf **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Stelt de rechtermarge in een alinea zonder overerving in. Schrijf **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Bepaalt of Rechts-naar-Links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Stelt de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving in. Een positieve waarde specificeert het percentage van de lettergrootte dat de witruimte moet zijn. Een negatieve waarde specificeert de grootte van de witruimte in punten. Schrijf **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Stelt de hoeveelheid ruimte voor de eerste regel in een alinea zonder overerving in. Een positieve waarde specificeert het percentage van de lettergrootte dat de witruimte moet zijn. Een negatieve waarde specificeert de grootte van de witruimte in punten. Schrijf **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Stelt de hoeveelheid ruimte tussen basisregels in een alinea in. Positieve waarde betekent percentage, negatieve – grootte in punten. Geen overerving toegepast. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n-de sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement unlocken. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waarschuwingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Bevrijdt alle interne datastructuren. |

## Opmerkingen


Deze klasse wordt gebruikt om alinea-opmaak-eigenschappen die voor een specifieke alinea zijn gedefinieerd te retourneren en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden krijgt die "onbepaald" betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te verkrijgen moet u de [ParagraphFormat::GetEffective](./geteffective/)-methode gebruiken die een [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)-instantie retourneert.

## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [IParagraphFormat](../iparagraphformat/)
* Klasse [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)