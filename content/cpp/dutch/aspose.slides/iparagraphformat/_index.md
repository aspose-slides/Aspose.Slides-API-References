---
title: IParagraphFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Deze klasse bevat de eigenschappen voor alinea-opmaak. In tegenstelling tot IParagraphFormatEffectiveData zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 3147
url: /nl/aspose.slides/iparagraphformat/
---
## IParagraphFormat klasse


Deze klasse bevat de eigenschappen voor alinea-opmaak. In tegenstelling tot [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) zijn alle eigenschappen van deze klasse schrijfbaar.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waarde-type in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige zwevend-kommagetallen vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige zwevend-kommagetallen vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Retourneert de tekstuitlijning in een alinea zonder overerving. Lees [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Retourneert het opsommingstekenformaat van de alinea. Alleen-lezen [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Retourneert het standaard gedeelte-formaat van een alinea. Geen overerving toegepast. Alleen-lezen [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Retourneert de standaard tabulatiegrootte zonder overerving. Lees **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Retourneert de diepte van de alinea. Waarde 0 betekent een ongedefinieerde waarde. Lees **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Retourneert een lettertype-uitlijning in een alinea zonder overerving. Lees [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Retourneert de eerste regel-insprong/hangende insprong van de alinea zonder overerving. Hangende insprong kan worden gedefinieerd met negatieve waarden. Lees **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Retourneert de linkermarge in een alinea zonder overerving. Lees **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Retourneert de rechtermarge in een alinea zonder overerving. Lees **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Bepaalt of rechts-naar-links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Retourneert de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in puntgrootte aan. Lees **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Retourneert de hoeveelheid ruimte vóór de eerste regel in een alinea zonder overerving. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in puntgrootte aan. Lees **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Retourneert de hoeveelheid ruimte tussen basislijnen in een alinea. Positieve waarde betekent percentage, negatieve waarde grootte in punten. Geen overerving toegepast. Lees **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Retourneert de tabulatie van een alinea op de opgegeven index. Geen overerving toegepast. Alleen-lezen [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Retourneert de tabulaties van een alinea. Geen overerving toegepast. Alleen-lezen [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Haalt de effectieve alinea-opmaakgegevens op met de overerving toegepast. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analog van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) schildobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieer-constructor. Kopieert niets, initialiseert slechts een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert slechts een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Stelt de tekstuitlijning in een alinea zonder overerving in. Schrijf [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Stelt de standaard tabulatiegrootte in zonder overerving. Schrijf **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Stelt de diepte van de alinea in. Waarde 0 betekent ongedefinieerde waarde. Schrijf **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Bepaalt of de Oost-Aziatische regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Stelt een lettertype-uitlijning in een alinea zonder overerving in. Schrijf [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Bepaalt of hangende interpunctie wordt gebruikt in een alinea. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Stelt de eerste regel-insprong/hangende insprong van de alinea in zonder overerving. Hangende insprong kan worden gedefinieerd met negatieve waarden. Schrijf **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Bepaalt of de Latijnse regeleinde wordt gebruikt in een alinea. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Stelt de linkermarge in een alinea zonder overerving in. Schrijf **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Stelt de rechtermarge in een alinea zonder overerving in. Schrijf **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Bepaalt of rechts-naar-links schrijven wordt gebruikt in een alinea. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Stelt de hoeveelheid ruimte na de laatste regel in een alinea zonder overerving in. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in puntgrootte aan. Schrijf **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Stelt de hoeveelheid ruimte vóór de eerste regel in een alinea zonder overerving in. Een positieve waarde geeft het percentage van de lettergrootte aan dat de witruimte moet zijn. Een negatieve waarde geeft de grootte van de witruimte in puntgrootte aan. Schrijf **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Stelt de hoeveelheid ruimte tussen basislijnen in een alinea in. Positieve waarde betekent percentage, negatieve waarde grootte in punten. Geen overerving toegepast. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) schildobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Bevrijdt alle interne datastructuren. |

## Opmerkingen

Deze klasse wordt gebruikt om alinea-opmaak eigenschappen die voor een specifieke alinea zijn gedefinieerd te retourneren en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden krijgt die "ongedefinieerd" betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te verkrijgen, moet u de [IParagraphFormat::GetEffective](./geteffective/)-methode gebruiken die een [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)-instantie retourneert.

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)