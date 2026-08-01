---
title: ArrayBase
second_title: Aspose.Slides voor C++ API-referentie
description: De dummy voor System.Array klasse (abstracte basis klasse voor alle arrays) kan op verzoek met functionaliteit worden gevuld.
type: docs
weight: 27
url: /nl/system/arraybase/
---
## ArrayBase klasse


De dummy voor [System.Array](../array/) klasse (abstracte basis klasse voor alle arrays) kan op verzoek met functionaliteit worden gevuld.

```cpp
class ArrayBase : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten volgens de C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetrouwe vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetrouwe vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **int32_t** [get_Length](./get_length/)() const | Retourneert een 32-bits geheel getal dat het totale aantal elementen in alle dimensies van de array vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-structuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../object/gethashcode/)-methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../object/gettype/)-aanroep. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een instantie van het door targetType beschreven type vertegenwoordigt. Analoge van de C# 'is'-operator. |
| void [Lock](../object/lock/)() | Implementeert C# lock()-statement voor locken. Roep direct aan of gebruik het [LockContext](../lockcontext/) bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te copy-constructeren. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, Initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te copy-constructeren. |
| virtual void * [raw_data_ptr](./raw_data_ptr/)() | Retourneert een pointer naar het eerste element van een eendimensionale array. Voor meerdimensionale arrays is het resultaat ongedefinieerd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analoge van de C# [Object.ToString()](../object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert de C# typeof([System.Object](../object/))-constructie. |
| void [Unlock](../object/unlock/)() | Implementeert C# lock()-statement voor ontgrendelen. Roep direct aan of gebruik het [LockContext](../lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../object/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)