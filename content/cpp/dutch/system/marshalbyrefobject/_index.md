---
title: MarshalByRefObject
second_title: Aspose.Slides voor C++ API-referentie
description: "Biedt toegang tot objecten over toepassingsdomeingrenzen heen in applicaties met remoting ingeschakeld. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Plaats deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 1080
url: /nl/system/marshalbyrefobject/
---
## MarshalByRefObject klasse

Biedt toegang tot objecten over toepassingsdomeingrenzen heen in toepassingen met remoting ingeschakeld. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Plaats deze klasse altijd in een [System::SmartPtr](../smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven.

```cpp
class MarshalByRefObject : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige zwevend-kommagelijke vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige zwevend-kommagelijke vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../object/gettype/)-aanroep. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C#-operator 'is'. |
| void [Lock](../object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../lockcontext/)-bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-templatesargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te wijzigen. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analoge van C# [Object.ToString()](../object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert de C# typeof([System.Object](../object/))-constructie. |
| void [Unlock](../object/unlock/)() | Implementeert het vrijgeven van het C# lock()-statement. Roep direct aan of gebruik het [LockContext](../lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../object/~object/)() | Vernietigt het object. Vrijmaakt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../object/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)