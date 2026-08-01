---
title: Tab
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een tabulatie voor een tekst voor.
type: docs
weight: 5370
url: /nl/aspose.slides/tab/
---
## Tabklasse

Stelt een tabulatie voor een tekst voor.

```cpp
class Tab : public Aspose::Slides::PVIObject,
            public Aspose::Slides::ITab
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **int32_t** [CompareTo](./compareto/)([System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\>) override | Vergelijkt de huidige instantie met een ander object van hetzelfde type. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [TabAlignment](../tabalignment/) [get_Alignment](./get_alignment/)() override | Retourneert de uitlijningsstijl van een tab. Lees [TabAlignment](../tabalignment/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate-object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert ouder [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| **double** [get_Position](./get_position/)() override | Retourneert positie van een tab. Het toewijzen van deze eigenschap kan de index van de tab in de collectie veranderen en de enumerator ongeldig maken. Lees **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-gegevensstructuur op die bij het object hoort. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert hashcode. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt echt type van object op. Analoge aan C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie is van het type dat wordt beschreven door targetType. Analoge aan C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarbewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge aan C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste types in staat. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert alleen nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde-type-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met opgegeven waarde. |
| void [set_Alignment](./set_alignment/)([TabAlignment](../tabalignment/)) override | Stelt uitlijningsstijl van een tab in. Schrijf [TabAlignment](../tabalignment/). |
| void [set_Position](./set_position/)(**double**) override | Stelt positie van een tab in. Het toewijzen van deze eigenschap kan de index van de tab in de collectie veranderen en de enumerator ongeldig maken. Schrijf **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Vermindert en retourneert gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [Tab](./tab/)(**double**, [TabAlignment](../tabalignment/)) | Creëert nieuwe [Tab](./) |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge aan C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt conversie van aangepaste objecten naar string in staat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert ontgrendeling van C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarbewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Vermindert zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [ITab](../itab/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)