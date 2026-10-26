---
title: BoxedValue
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een verpakte waarde voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject()-functie. Maak nooit een instantie van dit type op de stack of met de operator new, omdat dit runtime-fouten en/of assertiefouten kan veroorzaken. Omhul deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 105
url: /nl/system/boxedvalue/
---
## BoxedValue klasse

Stelt een verpakte waarde voor. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../makeobject/). Maak nooit een instantie van dit type op de stack of met de operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../smartptr/)-pointer en gebruik deze pointer om deze aan functies door te geven als argument.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van de verpakte waarde die door de klasse wordt weergegeven |

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const T\&) | Construeert een object dat de opgegeven verpakte waarde voorstelt. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Bepaalt de gelijkheid van de verpakte waarden die door het huidige en gespecificeerde object worden weergegeven. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| int [GetHashCode](./gethashcode/)() const override | Retourneert een hash-code voor het huidige object. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Haalt het werkelijke type van het object op. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | Retourneert de waarde die het type van de verpakte waarde van het huidige object vertegenwoordigt. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Retourneert de numerieke waarde van het verpakte object als dit kan worden gecast, anders nul. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van de C#-'is'-operator. |
| **bool** [is](./is/)() const | Bepaalt of het type van de verpakte waarde van het huidige object **V** is. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Bepaalt of het huidige object een verpakte waarde van een enum-type voorstelt. |
| void [Lock](../object/lock/)() | Implementeert de lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../lockcontext/)-bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van de C#-[Object.MemberwiseClone()](../object/memberwiseclone/)-methode. Maakt het klonen van aangepaste typen mogelijk. |
|  [Object](../object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieerconstructor. Kopieert niets, maar initialiseert een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Assignatie-operator. Kopieert niets, maar initialiseert een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Verpakt de waarde van een enumeratie-constante van de opgegeven enumeratie met de opgegeven naam. Een parameter geeft aan of hoofdlettergevoeligheid moet worden genegeerd bij het interpreteren van de tekenreeks die de naam van de enumeratie-constante specificeert. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Verpakt de waarde van een enumeratie-constante van de opgegeven enumeratie met de opgegeven naam. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van een gedeelde). Maakt het mogelijk om pointers in containers om te schakelen naar zwakke modus. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt de gedeelde referentieteller en retourneert deze. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Converteert de verpakte waarde die door het huidige object wordt vertegenwoordigd naar een string. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Converteert het verpakte object naar een string met behulp van een opgegeven opmaak-string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert de C# typeof([System.Object](../object/))-constructie. |
| const T\& [unbox](./unbox/)() const | Ontdoet de waarde die door het huidige object wordt vertegenwoordigd. |
| void [Unlock](../object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../object/~object/)() | Vernietigt het object. Bevrijdt alle interne datastructuren. |

## Zie ook

* Klasse [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)