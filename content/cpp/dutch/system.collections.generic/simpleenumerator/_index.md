---
title: SimpleEnumerator
second_title: Aspose.Slides voor C++ API-referentie
description: "Iteratorklasse voor eenvoudige containers die elementen direct houden met behulp van de rbegin() en rend() functies. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 508
url: /nl/system.collections.generic/simpleenumerator/
---
## SimpleEnumerator klasse


Iterator-klasse voor eenvoudige containers die elementen direct houden met behulp van de rbegin()- en rend()-functies. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies door te geven.

```cpp
template<typename Container,typename Element>class SimpleEnumerator : public System::Collections::Generic::BaseEnumerator<Container, typename Container::value_type>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Container | Containertype om doorheen te itereren. |
| Element | Elementtype. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [IEnumerator](../ienumerator/) * [AsVirtualizedIterator](../ienumerator/asvirtualizediterator/)() | Bereidt de iterator voor om te worden gebruikt door de VirtualizedIterator klasse. |
|  [BaseEnumerator](../baseenumerator/baseenumerator/)(const [Object::ptr](../../system/object/ptr/)\&, Container\&) | Initialiseert iterator. |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Kloont de huidige iterator. |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../ienumerator/current/)() const | Haalt het huidige element op. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Doet niets. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert een C#-achtige floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert een C#-achtige floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Element\> [get_Current](./get_current/)() const override | Haalt het 'huidige' element op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
|  [IEnumerator](../ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../ienumerator/incrementiterator/)() override | Verplaatst de iterator één stap vooruit. |
| void [InitializeIterator](../ienumerator/initializeiterator/)() override | Voert de eerste [MoveNext()](../ienumerator/movenext/)-aanroep uit en bereidt het enumerator-object voor om te worden gebruikt door VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van de C# 'is'-operator. |
| **bool** [IsValid](../baseenumerator/isvalid/)() const | Controleert of [MoveNext()](../baseenumerator/movenext/) is aangeroepen en het einde niet is bereikt. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| void [MarkOwnedByVirtualizedIterator](../ienumerator/markownedbyvirtualizediterator/)() | Markeert de enumerator die eigendom is van de virtualized iterator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
| **bool** [MoveNext](../baseenumerator/movenext/)() override | Enumerator-achtige incrementele stap. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignatie-operator. Kopieert niets echt, Initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [Reset](../baseenumerator/reset/)() override | Reset de enumerator om het opnieuw doorlopen van elementen mogelijk te maken. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van een gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en geeft de gedeelde referentieteller terug. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [SimpleEnumerator](./simpleenumerator/)([Object::ptr](../../system/object/ptr/), Container\&) | Creëert een eenvoudige iterator. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar een string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van het C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~IEnumerator](../ienumerator/~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [BaseEnumerator](../baseenumerator/)
* Namespace [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)