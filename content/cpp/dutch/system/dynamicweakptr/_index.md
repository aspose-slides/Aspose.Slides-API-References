---
title: DynamicWeakPtr
second_title: Aspose.Slides voor C++ API-referentie
description: Smart pointer-klasse die pointer-modus van template-argumenten van het opgeslagen object bijhoudt en deze bij elke toewijzing bijwerkt. Dit type is een pointer om de verwijdering van een ander object te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.
type: docs
weight: 781
url: /nl/system/dynamicweakptr/
---
## DynamicWeakPtr klasse


Smart pointer-klasse die pointer-modi van template-argumenten van het opgeslagen object bijhoudt en ze na elke toewijzing bijwerkt. Dit type is een pointer om de verwijdering van een ander object te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| Pointee | type. |
| trunkMode | Modus van de slimme pointer zelf, shared of weak. |
| weakLeafs | Indexen van template-argumenten van het opgeslagen type die op weak pointer-modus moeten worden gezet. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Accessor voor [begin()](../smartptr/begin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../smartptr/begin/)-methode. |
| auto [begin](../smartptr/begin/)() const | Accessor voor [begin()](../smartptr/begin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../smartptr/begin/)-methode. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converteert de pointer naar zijn eigen type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converteert de pointer naar het basistype met static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converteert de pointer naar een afgeleid type met dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converteert de pointer naar een afgeleid type met dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Accessor voor [cbegin()](../smartptr/cbegin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cbegin()](../smartptr/cbegin/)-methode. |
| auto [cend](../smartptr/cend/)() const | Accessor voor [cend()](../smartptr/cend/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cend()](../smartptr/cend/)-methode. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Converteert de pointer naar een ander type met const_cast op het aangewezen object. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Converteert de pointer naar een ander type met dynamic_cast op het aangewezen object. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Maakt een null smart pointer aan. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Maakt een smart pointer die naar het opgegeven object wijst. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Copy-constructeert een smart pointer. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Copy-constructeert een smart pointer. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Copy-constructeert een smart pointer. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Move-constructeert een smart pointer. |
| auto [end](../smartptr/end/)() | Accessor voor [end()](../smartptr/end/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../smartptr/end/)-methode. |
| auto [end](../smartptr/end/)() const | Accessor voor [end()](../smartptr/end/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../smartptr/end/)-methode. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Haalt het aangewezen object. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Haalt de pointer-modus. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Haalt het aangewezen object, maar stelt dat de pointer in gedeelde modus is. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Haalt het aantal gedeelde pointers dat naar het gerefereerde object bestaat, inclusief de huidige. Stelt dat de huidige pointer in gedeelde modus is. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Roept [GetHashCode()](../smartptr/gethashcode/) aan op het aangewezen object. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Haalt het momenteel gerefereerde object (indien aanwezig) of gooit een uitzondering. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Haalt het aangewezen object (indien aanwezig) of nullptr. Hetzelfde als [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Haalt het gerefereerde object. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Haalt het aangewezen object (indien aanwezig) of nullptr. Hetzelfde als [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Controleert of het aangewezen object van een specifiek type of een subtype is. Volgt de C# 'is'-semantiek. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Controleert of de pointer naar een ander object wijst dan het eigendom (gemaakt door een aliasing-constructeur). |
| **bool** [IsShared](../smartptr/isshared/)() const | Controleert of de pointer in gedeelde modus is. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Controleert of de pointer in zwakke modus is. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Controleert of de pointer niet null is. |
| **bool** [operator!](../smartptr/operator_not/)() const | Controleert of de pointer null is. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Haalt een referentie naar het aangewezen object. Stelt dat de pointer niet null is. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Staat toe leden van het gerefereerde object te benaderen. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../smartptr/)-klasse. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../smartptr/)-klasse. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Move-assignert een smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Copy-assignert een smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Copy-assignert een smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Assigns een smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Stelt een smart pointer in op null. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Controleert of de smart pointer null is. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Verwijdert aliasing (gecreëerd door een aliasing-constructeur) van de pointer, en zorgt ervoor dat het dezelfde object beheert (indien gedeeld) of volgt (indien zwak) als waarnaar het wijst. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Stelt het aangewezen object in. |
| void [reset](../smartptr/reset/)() | Laat de pointer naar nullptr wijzen. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Stelt de pointer-modus in. Kan de referentietellingen van het gerefereerde object wijzigen. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Roept SetTemplateWeakPtr()-methode aan op het aangewezen object (indien aanwezig). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Maakt een [SmartPtr](../smartptr/)-object van vereiste modus aan. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Maakt een null-pointer [SmartPtr](../smartptr/)-object van vereiste modus aan. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Maakt een [SmartPtr](../smartptr/) die naar het opgegeven object wijst, of converteert een ruwe pointer naar [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Copy-constructeert een [SmartPtr](../smartptr/)-object. Beide pointers wijzen daarna naar hetzelfde object. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Copy-constructeert een [SmartPtr](../smartptr/)-object. Beide pointers wijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Move-constructeert een [SmartPtr](../smartptr/)-object. Verwisselt in feite twee pointers als ze beide dezelfde modus hebben. x kan na de oproep onbruikbaar zijn. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converteert het type van de gerefereerde array door een nieuwe array van een ander type te maken. Handig wanneer er in C# een array type-cast bestaat die niet wordt ondersteund in C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Initialiseert een lege array. Wordt gebruikt om enkele C#-codeconstructies te vertalen. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Construeert een [SmartPtr](../smartptr/) die eigendomsinformatie deelt met de initiële waarde van ptr, maar een niet-gerelateerd en onbeheerd pointer p bevat. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Converteert de pointer naar een ander type met static_cast op het aangewezen object. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Converteert elk pointertype naar een pointer naar [Object](../object/). Vereist niet dat het Pointee_-type volledig is. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Snelkoppeling om een [System::TypeInfo](../typeinfo/)-object te krijgen voor het Pointee_-type. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Vernietigt een [SmartPtr](../smartptr/)-object. Indien nodig, vermindert de referentieteller van het aangewezen object en verwijdert het. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) basisclass-alias. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Zelftype-alias. |
| [Pointee_](./pointee_/) | Aangewezen type. |

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)