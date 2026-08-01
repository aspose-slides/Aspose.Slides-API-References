---
title: QueuePtr
second_title: Aspose.Slides voor C++ API-referentie
description: Queue-pointer. Dit type is een pointer om de verwijdering van andere objecten te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.
type: docs
weight: 482
url: /nl/system.collections.generic/queueptr/
---
## QueuePtr klasse


[Queue](../queue/) pointer. Dit type is een pointer om de verwijdering van andere objecten te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Toegangsmethode voor [begin()](../../system/smartptr/begin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../../system/smartptr/begin/)-methode. |
| auto [begin](../../system/smartptr/begin/)() const | Toegangsmethode voor [begin()](../../system/smartptr/begin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../../system/smartptr/begin/)-methode. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast de pointer naar zijn eigen type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast de pointer naar het basistype met static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast de pointer naar het afgeleide type met dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Cast de pointer naar het afgeleide type met dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Toegangsmethode voor [cbegin()](../../system/smartptr/cbegin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cbegin()](../../system/smartptr/cbegin/)-methode. |
| auto [cend](../../system/smartptr/cend/)() const | Toegangsmethode voor [cend()](../../system/smartptr/cend/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cend()](../../system/smartptr/cend/)-methode. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Cast de pointer naar een ander type met const_cast op het aangewezen object. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Cast de pointer naar een ander type met dynamic_cast op het aangewezen object. |
| auto [end](../../system/smartptr/end/)() | Toegangsmethode voor [end()](../../system/smartptr/end/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../../system/smartptr/end/)-methode. |
| auto [end](../../system/smartptr/end/)() const | Toegangsmethode voor [end()](../../system/smartptr/end/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../../system/smartptr/end/)-methode. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Haalt het aangewezen object op. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Haalt de pointermodus op. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Haalt het aangewezen object op, maar beweert dat de pointer in gedeelde modus is. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Haalt het aantal gedeelde pointers op dat bestaat naar het gerefereerde object, inclusief de huidige. Beweert dat de huidige pointer zich in gedeelde modus bevindt. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Roept [GetHashCode()](../../system/smartptr/gethashcode/) aan op het aangewezen object. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Haalt het momenteel gerefereerde object op (indien aanwezig) of gooit een uitzondering. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Haalt het aangewezen object op (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Haalt het gerefereerde object op. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Haalt het aangewezen object op (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Controleert of het aangewezen object van een specifiek type of een afgeleid type is. Volgt de C# 'is' semantiek. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Controleert of de pointer naar een ander object dan het eigendom wijst (gemaakt door een aliasing-constructor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Controleert of de pointer zich in gedeelde modus bevindt. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Controleert of de pointer zich in zwakke modus bevindt. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Controleert of de pointer niet null is. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Controleert of de pointer null is. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Haalt een referentie op naar het aangewezen object. Beweert dat de pointer niet null is. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Staat toe leden van het gerefereerde object te benaderen. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../../system/smartptr/)-klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../../system/smartptr/)-klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Verplaatst toewijzing van [SmartPtr](../../system/smartptr/)-object. x wordt onbruikbaar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopieert toewijzing van [SmartPtr](../../system/smartptr/)-object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopieert toewijzing van [SmartPtr](../../system/smartptr/)-object. Voert de vereiste typeconversies uit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Wijst een ruwe pointer toe aan [SmartPtr](../../system/smartptr/)-object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Stelt de pointerwaarde in op nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Controleert of de pointer naar nullptr wijst. |
|  [QueuePtr](./queueptr/)() | Construeert een null-pointer. |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | Construeert een pointer naar een specifieke queue. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Verwijdert aliasing (gecreëerd door een aliasing-constructor) van de pointer, zorgt ervoor dat deze (indien gedeeld) beheert of (indien zwak) volgt het zelfde object waarnaar hij wijst. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Stelt het aangewezen object in. |
| void [reset](../../system/smartptr/reset/)() | Laat de pointer naar nullptr wijzen. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Stelt de pointermodus in. Kan de referentietellers van het gerefereerde object wijzigen. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Roept SetTemplateWeakPtr()-methode aan op het aangewezen object (indien aanwezig). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Creëert een [SmartPtr](../../system/smartptr/)-object in de vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Creëert een null-pointer [SmartPtr](../../system/smartptr/)-object in de vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Creëert een [SmartPtr](../../system/smartptr/) die wijst naar het opgegeven object, of zet een ruwe pointer om naar [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopieert een [SmartPtr](../../system/smartptr/)-object. Beide pointers wijzen daarna naar hetzelfde object. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopieert een [SmartPtr](../../system/smartptr/)-object. Beide pointers wijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Verplaatst een [SmartPtr](../../system/smartptr/)-object. Effectief wisselt het twee pointers uit, als ze dezelfde modus hebben. x kan na de oproep onbruikbaar zijn. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Zet het type van de gerefereerde array om door een nieuwe array van een ander type te creëren. Handig als er in C# een array-typecast bestaat die niet ondersteund wordt in C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialiseert een lege array. Wordt gebruikt om sommige C#-codeconstructies te vertalen. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construeert een [SmartPtr](../../system/smartptr/) die eigendomsinformatie deelt met de initiële waarde van ptr, maar een niet-gerelateerd en onbeheerd pointer p vasthoudt. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Cast de pointer naar een ander type met static_cast op het aangewezen object. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Zet elk pointertype om naar een pointer naar [Object](../../system/object/). Vereist niet dat het Pointee_-type compleet is. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Snelkoppeling om het [System::TypeInfo](../../system/typeinfo/)-object voor het Pointee_-type te verkrijgen. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Vernietigt [SmartPtr](../../system/smartptr/)-object. Indien nodig verlaagt het de referentieteller van het aangewezen object en verwijdert het object. |

## Zie ook

* Klasse [SmartPtr](../../system/smartptr/)
* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)