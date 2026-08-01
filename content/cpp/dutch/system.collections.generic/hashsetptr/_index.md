---
title: HashSetPtr
second_title: Aspose.Slides voor C++ API-referentie
description: Pointer om HashSet-referenties bij te houden. Dit type is een pointer om de verwijdering van een ander object te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.
type: docs
weight: 235
url: /nl/system.collections.generic/hashsetptr/
---
## HashSetPtr klasse


Pointer om [HashSet](../hashset/) referenties bij te houden. Dit type is een pointer om de verwijdering van een ander object te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde, hetzij per const-referentie.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Toegangsfunctie voor de [begin()](../../system/smartptr/begin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [begin()](../../system/smartptr/begin/) methode. |
| auto [begin](../../system/smartptr/begin/)() const | Toegangsfunctie voor de [begin()](../../system/smartptr/begin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [begin()](../../system/smartptr/begin/) methode. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast pointer naar zijn eigen type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast pointer naar basistype met static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast pointer naar afgeleid type met dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast pointer naar afgeleid type met dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Toegangsfunctie voor de [cbegin()](../../system/smartptr/cbegin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [cbegin()](../../system/smartptr/cbegin/) methode. |
| auto [cend](../../system/smartptr/cend/)() const | Toegangsfunctie voor de [cend()](../../system/smartptr/cend/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [cend()](../../system/smartptr/cend/) methode. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Cast pointer naar een ander type met const_cast op het geadresseerde object. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Cast pointer naar een ander type met dynamic_cast op het geadresseerde object. |
| auto [end](../../system/smartptr/end/)() | Toegangsfunctie voor de [end()](../../system/smartptr/end/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [end()](../../system/smartptr/end/) methode. |
| auto [end](../../system/smartptr/end/)() const | Toegangsfunctie voor de [end()](../../system/smartptr/end/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [end()](../../system/smartptr/end/) methode. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Haalt geadresseerd object op. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Haalt pointer-modus op. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Haalt geadresseerd object op, maar stelt dat de pointer in gedeelde modus is. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Haalt het aantal gedeelde pointers op dat bestaat naar het gerefereerde object, inclusief de huidige. Stelt dat de huidige pointer in gedeelde modus is. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Roept [GetHashCode()](../../system/smartptr/gethashcode/) aan op geadresseerd object. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Haalt momenteel gerefereerd object op (indien aanwezig) of gooit een uitzondering. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Haalt geadresseerd object op (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Haalt gerefereerd object op. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Haalt geadresseerd object op (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
|  [HashSetPtr](./hashsetptr/)() | Constructor voor null-pointer. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | Copy-constructor. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Controleert of geadresseerd object van een specifiek type of een onderliggend type is. Volgt C# 'is' semantiek. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Controleert of de pointer naar een ander object wijst dan het eigendom (gecreëerd door een aliasing-constructor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Controleert of de pointer in gedeelde modus is. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Controleert of de pointer in zwakke modus is. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Controleert of de pointer niet null is. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Controleert of de pointer null is. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Haalt referentie naar geadresseerd object op. Stelt dat de pointer niet null is. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Staat toe leden van het gerefereerde object te benaderen. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../../system/smartptr/) klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../../system/smartptr/) klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Voert move-toewijzing uit op [SmartPtr](../../system/smartptr/) object. x wordt onbruikbaar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Voert copy-toewijzing uit op [SmartPtr](../../system/smartptr/) object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Voert copy-toewijzing uit op [SmartPtr](../../system/smartptr/) object. Voert benodigde typeconversies uit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Wijs een ruwe pointer toe aan [SmartPtr](../../system/smartptr/) object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Stelt de pointerwaarde in op nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Controleert of de pointer naar nullptr wijst. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Verwijdert aliasing (gecreëerd door een aliasing-constructor) van de pointer, en zorgt ervoor dat deze (indien gedeeld) beheert of (indien zwak) volgt hetzelfde object waarnaar hij wijst. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Stelt geadresseerd object in. |
| void [reset](../../system/smartptr/reset/)() | Laat de pointer naar nullptr wijzen. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Stelt pointer-modus in. Kan de referentie-tellers van het gerefereerde object wijzigen. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Roept SetTemplateWeakPtr() methode aan op geadresseerd object (indien aanwezig). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Creëert [SmartPtr](../../system/smartptr/) object met vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Creëert null-pointer [SmartPtr](../../system/smartptr/) object met vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Creëert [SmartPtr](../../system/smartptr/) die wijst naar het opgegeven object, of converteert ruwe pointer naar [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Copy-constructeert [SmartPtr](../../system/smartptr/) object. Beide pointers wijzen daarna naar hetzelfde object. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Copy-constructeert [SmartPtr](../../system/smartptr/) object. Beide pointers wijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move-constructeert [SmartPtr](../../system/smartptr/) object. Verwisselt in feite twee pointers als beide dezelfde modus hebben. x kan na de oproep onbruikbaar zijn. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converteert type van gerefereerde array door een nieuwe array van ander type te maken. Nuttig als er in C# een arraytype-cast is die niet wordt ondersteund in C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialiseert lege array. Gebruikt om sommige C# codeconstructies te vertalen. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construeert een [SmartPtr](../../system/smartptr/) die eigendomsinformatie deelt met de initiële waarde van ptr, maar een ongerelateerde en onbeheerde pointer p bevat. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Cast pointer naar een ander type met static_cast op geadresseerd object. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converteert elk pointertype naar pointer naar [Object](../../system/object/). Vereist niet dat het Pointee_ type compleet is. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Snelkoppeling om [System::TypeInfo](../../system/typeinfo/) object voor het Pointee_ type te krijgen. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Vernietigt [SmartPtr](../../system/smartptr/) object. Indien nodig, verlaagt de referentieteller van het geadresseerde object en verwijdert het object. |

## Zie ook

* Klasse [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)