---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een verzameling van delegaten voor. Dit type moet op de stack worden gealloceerd en doorgegeven aan functies per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 1093
url: /nl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> klasse


Stelt een verzameling van delegaten voor. Dit type moet op de stack worden gealloceerd en doorgegeven aan functies per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ReturnType | Retourtype van de aanroepbare entiteiten waarnaar elke delegate in de verzameling wijst |
| ArgumentTypes | Argumentenlijst van de aanroepbare entiteiten waarnaar elke delegate in de verzameling wijst |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NIET GEREALISEERD. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Voegt de opgegeven delegate toe aan de verzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Voegt het opgegeven functieobject toe aan de delegateverzameling. Het functieobject wordt geconverteerd naar het Callback-delegatietype voordat het aan de verzameling wordt toegevoegd. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Voegt het opgegeven MulticastDelegate-object toe aan de delegateverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Voegt de opgegeven niet-statische methode van het opgegeven object toe aan de delegateverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Voegt de opgegeven niet-statische methode van het opgegeven object toe aan de delegateverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Verwijdert de opgegeven delegate uit de delegateverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Verwijdert de opgegeven niet-statische methode van het opgegeven object uit de delegateverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Verwijdert de opgegeven niet-statische methode van het opgegeven object uit de delegateverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Verwijdert het opgegeven MulticastDelegate-object uit de delegateverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Verwijdert alle delegaten uit de delegateverzameling. |
| **bool** [empty](./empty/)() const | Bepaalt of de delegateverzameling leeg is. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NIET GEREALISEERD. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Roep alle momenteel aanwezige delegaten in de delegatenverzameling op. Delegaten worden opgeroepen in dezelfde volgorde als waarin ze aan de verzameling zijn toegevoegd. De methode blokkeert zolang de delegaten worden uitgevoerd. |
| **bool** [IsNull](./isnull/)() const | Bepaalt of de delegateverzameling leeg is. |
|  [MulticastDelegate](./multicastdelegate/)() | Construeert een lege verzameling. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Equivalent aan de standaardconstructor. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Voert een ondiepe kopie uit van de delegateverzameling. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Move-constructor. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Construeert een instantie en plaatst de opgegeven delegate in de delegatenverzameling. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Construeert een instantie en plaatst de opgegeven waarde in de delegatenverzameling. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Construeert een instantie en plaatst de opgegeven waarde in de delegatenverzameling. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Bepaalt of de delegateverzameling niet leeg is. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Bepaalt of twee instanties van MulticastDelegate - het huidige object en het opgegeven object - ongelijk zijn. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Roep alle momenteel aanwezige delegaten in de delegatenverzameling op. Delegaten worden opgeroepen in dezelfde volgorde als waarin ze aan de verzameling zijn toegevoegd. De operator blokkeert zolang de delegaten worden uitgevoerd. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Voegt de opgegeven delegate toe aan de verzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Verwijdert de opgegeven delegate uit de delegateverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Kenst de delegatenverzameling die wordt vertegenwoordigd door het opgegeven object toe aan het huidige object. Als gevolg hiervan wijzen beide objecten naar dezelfde delegatenverzameling. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Move-assignatieoperator. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Bepaalt of de delegateverzameling leeg is. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Bepaalt of twee instanties van MulticastDelegate - het huidige object en het opgegeven object - gelijk zijn. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Verwijdert de ingesloten callbacks die leeg zijn (die niets aanroepen). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retourneert een referentie naar het [TypeInfo](../typeinfo/) object dat de type-informatie van de MulticastDelegate klasse vertegenwoordigt. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destruktor. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Callback](./callback/) | Het type van de delegaten die worden vertegenwoordigd door de MulticastDelegate klasse. |
| [Function](./function/) | Het type van de functie die gerelateerd is aan de delegate-handtekening. |
## Zie ook

* namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)