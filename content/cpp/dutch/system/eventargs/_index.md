---
title: EventArgs
second_title: Aspose.Slides voor C++ API-referentie
description: "De basisklasse voor klassen die een context vertegenwoordigen die wordt doorgegeven aan de gebeurtenisabonnees wanneer een gebeurtenis wordt geactiveerd. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 820
url: /nl/system/eventargs/
---
## EventArgs klasse

De basisklasse voor klassen die een context vertegenwoordigen die wordt doorgegeven aan de gebeurtenisabonnees wanneer een gebeurtenis wordt geactiveerd. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtimefouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class EventArgs : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
|  [EventArgs](./eventargs/)() | Constructor. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../object/gethashcode/) methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt daadwerkelijke type van object op. Analog van C# [System.Object.GetType()](../object/gettype/) aanroep. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleer of object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analog van C# 'is' operator. |
| void [Lock](../object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-constructor. Kopieert echt niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te copy-constructoren. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert echt niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te copy-constructoren. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Vermindert gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stel het n'te sjabloonargument in als een weak-pointer (in plaats van shared). Staat toe om pointers in containers naar weak-modus te schakelen. |
| int [SharedCount](../object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog van C# [Object.ToString()](../object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert C# typeof([System.Object](../object/)) constructie. |
| void [Unlock](../object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt weak-referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt weak-referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Velden

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Een statisch lid dat een "lege" [EventArgs](./) shared pointer (null-pointer) vertegenwoordigt. |

## Zie ook

* Klasse [Object](../object/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)