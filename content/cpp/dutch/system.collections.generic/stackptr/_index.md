---
title: StackPtr
second_title: Aspose.Slides voor C++ API-referentie
description: Stackpointer. Dit type is een pointer om de verwijdering van andere objecten te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.
type: docs
weight: 612
url: /nl/system.collections.generic/stackptr/
---
## StackPtr klasse

[Stack](../stack/) pointer. Dit type is een pointer om de verwijdering van andere objecten te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Elementtype. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accessor voor [begin()](../../system/smartptr/begin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../../system/smartptr/begin/)-methode. |
| auto [begin](../../system/smartptr/begin/)() const | Accessor voor [begin()](../../system/smartptr/begin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../../system/smartptr/begin/)-methode. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast pointer naar zijn eigen type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast pointer naar basistype met static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast pointer naar afgeleid type met dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast pointer naar afgeleid type met dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accessor voor [cbegin()](../../system/smartptr/cbegin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cbegin()](../../system/smartptr/cbegin/)-methode. |
| auto [cend](../../system/smartptr/cend/)() const | Accessor voor [cend()](../../system/smartptr/cend/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cend()](../../system/smartptr/cend/)-methode. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Cast pointer naar ander type met const_cast op het aangewezen object. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Cast pointer naar ander type met dynamic_cast op het aangewezen object. |
| auto [end](../../system/smartptr/end/)() | Accessor voor [end()](../../system/smartptr/end/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../../system/smartptr/end/)-methode. |
| auto [end](../../system/smartptr/end/)() const | Accessor voor [end()](../../system/smartptr/end/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../../system/smartptr/end/)-methode. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Haalt het aangewezen object. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Haalt de pointermodus. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Haalt het aangewezen object, maar eist dat de pointer in gedeelde modus is. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Geeft het aantal gedeelde pointers naar het verwezen object, inclusief de huidige. Eist dat de huidige pointer in gedeelde modus is. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Roept [GetHashCode()](../../system/smartptr/gethashcode/) aan op het aangewezen object. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Haalt het momenteel verwezen object (indien aanwezig) of gooit een uitzondering. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Haalt het aangewezen object (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Haalt het verwezen object. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Haalt het aangewezen object (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Controleert of het aangewezen object van een specifiek type of een afgeleid type is. Volgt de C# 'is'-semantiek. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Controleert of de pointer naar een ander object wijst dan het eigendom (gecreëerd door een aliasing-constructor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Controleert of de pointer in gedeelde modus is. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Controleert of de pointer in zwakke modus is. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Controleert of de pointer niet null is. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Controleert of de pointer null is. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Haalt een referentie naar het aangewezen object. Eist dat de pointer niet null is. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Staat toe leden van het verwezen object te benaderen. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../../system/smartptr/)-klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../../system/smartptr/)-klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Voert move-assign uit op [SmartPtr](../../system/smartptr/)-object. x wordt onbruikbaar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Voert copy-assign uit op [SmartPtr](../../system/smartptr/)-object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Voert copy-assign uit op [SmartPtr](../../system/smartptr/)-object. Voert vereiste typeconversies uit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Wijst een ruwe pointer toe aan [SmartPtr](../../system/smartptr/)-object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Stelt pointerwaarde in op nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Controleert of de pointer naar nullptr wijst. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Verwijdert aliasing (gecreëerd door een aliasing-constructor) van de pointer, en zorgt ervoor dat deze (indien gedeeld) of volgt (indien zwak) hetzelfde object waarnaar hij wijst. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Stelt het aangewezen object in. |
| void [reset](../../system/smartptr/reset/)() | Laat de pointer naar nullptr wijzen. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Stelt pointermodus in. Kan de referentietellers van het verwezen object wijzigen. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Roept SetTemplateWeakPtr()-methode aan op het aangewezen object (indien aanwezig). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Creëert een [SmartPtr](../../system/smartptr/)-object in de vereiste modus. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Creëert een null-pointer [SmartPtr](../../system/smartptr/)-object in de vereiste modus. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Creëert een [SmartPtr](../../system/smartptr/) die naar het opgegeven object wijst, of converteert een ruwe pointer naar [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Copy-constructeert een [SmartPtr](../../system/smartptr/)-object. Beide pointers wijzen daarna naar hetzelfde object. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Copy-constructeert een [SmartPtr](../../system/smartptr/)-object. Beide pointers wijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move-constructeert een [SmartPtr](../../system/smartptr/)-object. Verwisselt effectief twee pointers als ze dezelfde modus hebben. x kan na de aanroep onbruikbaar zijn. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converteert het type van de verwezen array door een nieuwe array van een ander type te maken. Nuttig indien in C# een array-typecast bestaat die niet wordt ondersteund in C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialiseert een lege array. Gebruikt om enkele C#-codeconstructies te vertalen. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construeert een [SmartPtr](../../system/smartptr/) die eigendomsinformatie deelt met de initiële waarde van ptr, maar een ongeassocieerde en onbeheerde pointer p bevat. |
| [StackPtr](./stackptr/)() | Construeert een null-pointer. |
| [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | Construeert een pointer die naar een specifieke stack verwijst. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Cast pointer naar ander type met static_cast op het aangewezen object. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converteert elk pointertype naar een pointer naar [Object](../../system/object/). Vereist niet dat het Pointee_-type compleet is. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Snelkoppeling om [System::TypeInfo](../../system/typeinfo/)-object te verkrijgen voor het Pointee_-type. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Vernietigt het [SmartPtr](../../system/smartptr/)-object. Verlaagt indien nodig de referentieteller van het aangewezen object en verwijdert het object. |

## Zie ook

* Klasse [SmartPtr](../../system/smartptr/)
* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)