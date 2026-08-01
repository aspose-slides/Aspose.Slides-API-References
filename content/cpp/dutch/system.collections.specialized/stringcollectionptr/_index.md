---
title: StringCollectionPtr
second_title: Aspose.Slides voor C++ API-referentie
description: String-collectie-pointer met toegang-operator.
type: docs
weight: 40
url: /nl/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr klasse

String-collectie-pointer met toegang-operator.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Toegangsfunctie voor de [begin()](../../system/smartptr/begin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [begin()](../../system/smartptr/begin/)-methode. |
| auto [begin](../../system/smartptr/begin/)() const | Toegangsfunctie voor de [begin()](../../system/smartptr/begin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [begin()](../../system/smartptr/begin/)-methode. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Converteert de pointer naar zijn eigen type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Converteert de pointer naar het basistype met static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Converteert de pointer naar een afgeleid type met dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Converteert de pointer naar een afgeleid type met dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Toegangsfunctie voor de [cbegin()](../../system/smartptr/cbegin/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [cbegin()](../../system/smartptr/cbegin/)-methode. |
| auto [cend](../../system/smartptr/cend/)() const | Toegangsfunctie voor de [cend()](../../system/smartptr/cend/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [cend()](../../system/smartptr/cend/)-methode. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Converteert de pointer naar een ander type met const_cast op het aangewezen object. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Converteert de pointer naar een ander type met dynamic_cast op het aangewezen object. |
| auto [end](../../system/smartptr/end/)() | Toegangsfunctie voor de [end()](../../system/smartptr/end/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [end()](../../system/smartptr/end/)-methode. |
| auto [end](../../system/smartptr/end/)() const | Toegangsfunctie voor de [end()](../../system/smartptr/end/)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de [end()](../../system/smartptr/end/)-methode. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Geeft het aangewezen object terug. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Geeft de pointermodus terug. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Geeft het aangewezen object terug, maar stelt dat de pointer zich in gedeelde modus bevindt. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Geeft het aantal gedeelde pointers naar het gerefereerde object terug, inclusief de huidige. Stelt dat de huidige pointer zich in gedeelde modus bevindt. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Roept [GetHashCode()](../../system/smartptr/gethashcode/) aan op het aangewezen object. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Geeft het momenteel gerefereerde object terug (indien aanwezig) of werpt een uitzondering. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Geeft het aangewezen object terug (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Geeft het gerefereerde object terug. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Geeft het aangewezen object terug (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Controleert of het aangewezen object van een specifiek type is of van een afgeleid type. Volgt de C# 'is'-semantiek. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Controleert of de pointer naar een ander object wijst dan het eigendom (gecreëerd door een aliasing constructor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Controleert of de pointer zich in gedeelde modus bevindt. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Controleert of de pointer zich in zwakke modus bevindt. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Controleert of de pointer niet null is. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Controleert of de pointer null is. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Geeft een referentie naar het aangewezen object terug. Stelt dat de pointer niet null is. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Staat toe leden van het gerefereerde object te benaderen. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Biedt minder-vergelijkingssemantiek voor de [SmartPtr](../../system/smartptr/)-klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Biedt minder-vergelijkingssemantiek voor de [SmartPtr](../../system/smartptr/)-klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Verplaatst een [SmartPtr](../../system/smartptr/)-object via toewijzing. x wordt onbruikbaar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopie-toewijzing van [SmartPtr](../../system/smartptr/)-object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopie-toewijzing van [SmartPtr](../../system/smartptr/)-object. Voert de benodigde typeconversies uit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Wijst een ruwe pointer toe aan een [SmartPtr](../../system/smartptr/)-object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Stelt de pointerwaarde in op nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Controleert of de pointer naar nullptr wijst. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | Toegangsfunctie. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Verwijdert aliasing (gecreëerd door een aliasing constructor) van de pointer, en zorgt ervoor dat deze (bij gedeeld) het object beheert of (bij zwak) volgt datzelfde object waarnaar hij wijst. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Stelt het aangewezen object in. |
| void [reset](../../system/smartptr/reset/)() | Laat de pointer naar nullptr wijzen. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Stelt de pointermodus in. Kan de referentietellers van het gerefereerde object wijzigen. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Roept de SetTemplateWeakPtr()-methode aan op het aangewezen object (indien aanwezig). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Creëert een [SmartPtr](../../system/smartptr/)-object met de vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Creëert een null-pointer [SmartPtr](../../system/smartptr/)-object met de vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Creëert een [SmartPtr](../../system/smartptr/) die naar het opgegeven object wijst, of converteert een ruwe pointer naar [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopie-constructie van een [SmartPtr](../../system/smartptr/)-object. Beide pointers verwijzen daarna naar hetzelfde object. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopie-constructie van een [SmartPtr](../../system/smartptr/)-object. Beide pointers verwijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Verplaats-constructie van een [SmartPtr](../../system/smartptr/)-object. Effectief verwisselt het twee pointers, mits beide dezelfde modus hebben. x kan onbruikbaar worden na de oproep. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converteert het type van een gerefereerde array door een nieuwe array van een ander type te maken. Handig wanneer er in C# een array-typecast bestaat die niet wordt ondersteund in C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialiseert een lege array. Wordt gebruikt om bepaalde C#-codeconstructies te vertalen. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construeert een [SmartPtr](../../system/smartptr/) die de eigendomsinformatie deelt met de initiële waarde van ptr, maar een ongerelateerde en onbeheerste pointer p bevat. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Converteert de pointer naar een ander type met static_cast op het aangewezen object. |
|  [StringCollectionPtr](./stringcollectionptr/)() | Construeert een null-pointer. |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | Construeert een pointer naar een specifieke collectie. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converteert elk pointertype naar een pointer naar [Object](../../system/object/). Vereist niet dat het Pointee_-type volledig is. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Snelkoppeling om het [System::TypeInfo](../../system/typeinfo/)-object voor het Pointee_-type te verkrijgen. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Vernietigt het [SmartPtr](../../system/smartptr/)-object. Indien nodig wordt de referentieteller van het aangewezen object verlaagd en wordt het object verwijderd. |

## Zie ook

* Klasse [SmartPtr](../../system/smartptr/)
* Naamruimte [System::Collections::Specialized](../)
* Library [Aspose.Slides](../../)