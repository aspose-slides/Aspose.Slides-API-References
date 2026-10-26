---
title: ListPtr
second_title: Aspose.Slides voor C++ API-referentie
description: Lijstpointer met toegangsmethoden. Dit type is een pointer om de verwijdering van andere objecten te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.
type: docs
weight: 456
url: /nl/system.collections.generic/listptr/
---
## ListPtr klasse

[List](../list/) pointer met toegangsmethoden. Dit type is een pointer om de verwijdering van andere objecten te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde of per const-referentie.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accessor voor [begin()](../../system/smartptr/begin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../../system/smartptr/begin/) methode. |
| auto [begin](../../system/smartptr/begin/)() const | Accessor voor [begin()](../../system/smartptr/begin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../../system/smartptr/begin/) methode. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Zet pointer om naar zijn eigen type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Zet pointer om naar basistype met static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Zet pointer om naar afgeleid type met dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Zet pointer om naar afgeleid type met dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accessor voor [cbegin()](../../system/smartptr/cbegin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cbegin()](../../system/smartptr/cbegin/) methode. |
| auto [cend](../../system/smartptr/cend/)() const | Accessor voor [cend()](../../system/smartptr/cend/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cend()](../../system/smartptr/cend/) methode. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Zet pointer om naar een ander type met const_cast op het gepointeerde object. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Zet pointer om naar een ander type met dynamic_cast op het gepointeerde object. |
| auto [end](../../system/smartptr/end/)() | Accessor voor [end()](../../system/smartptr/end/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../../system/smartptr/end/) methode. |
| auto [end](../../system/smartptr/end/)() const | Accessor voor [end()](../../system/smartptr/end/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../../system/smartptr/end/) methode. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Verkrijgt het gepointeerde object. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Verkrijgt de pointermodus. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Verkrijgt het gepointeerde object, maar controleert dat de pointer zich in gedeelde modus bevindt. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Verkrijgt het aantal gedeelde pointers die naar het referentieobject bestaan, inclusief de huidige. Controleert dat de huidige pointer zich in gedeelde modus bevindt. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Roep [GetHashCode()](../../system/smartptr/gethashcode/) aan op het gepointeerde object. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Verkrijgt het momenteel gerefereerde object (indien aanwezig) of gooit een uitzondering. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Verkrijgt het gepointeerde object (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Verkrijgt het gerefereerde object. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Verkrijgt het gepointeerde object (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Controleert of het gepointeerde object van een specifiek type is of van een afgeleid type. Volgt de C# 'is' semantiek. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Controleert of de pointer naar een ander object wijst dan het eigendom (gemaakt door een aliasing constructor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Controleert of de pointer zich in gedeelde modus bevindt. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Controleert of de pointer zich in zwakke modus bevindt. |
|  [ListPtr](./listptr/)(std::nullptr_t) | Initialiseert null-pointer. |
|  [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | Initialiseert pointer naar opgegeven lijst. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Controleert of de pointer niet null is. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Controleert of de pointer null is. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Verkrijgt referentie naar het gepointeerde object. Controleert dat de pointer niet null is. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Staat toe leden van het gerefereerde object te benaderen. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../../system/smartptr/) klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Biedt minder-vergelijkingssemantiek voor [SmartPtr](../../system/smartptr/) klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Verplaatst toewijzing van [SmartPtr](../../system/smartptr/) object. x wordt onbruikbaar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopieert toewijzing van [SmartPtr](../../system/smartptr/) object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopieert toewijzing van [SmartPtr](../../system/smartptr/) object. Voert vereiste typeconversies uit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Wijs ruwe pointer toe aan [SmartPtr](../../system/smartptr/) object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Stelt pointerwaarde in op nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Controleert of [List](../list/) pointer null is. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | Toegangsmethode. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | Toegangsmethode. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Verwijdert aliasing (gemaakt door een aliasing constructor) van de pointer, en zorgt ervoor dat deze (indien gedeeld) beheert of (indien zwak) bijhoudt naar hetzelfde object waarnaar hij wijst. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Stelt gepointeerd object in. |
| void [reset](../../system/smartptr/reset/)() | Laat de pointer wijzen naar nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Stelt pointermodus in. Kan de referentietellers van het gerefereerde object wijzigen. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Roep SetTemplateWeakPtr() methode aan op het gepointeerde object (indien aanwezig). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Creëert [SmartPtr](../../system/smartptr/) object van de vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Creëert null-pointer [SmartPtr](../../system/smartptr/) object van de vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Creëert [SmartPtr](../../system/smartptr/) die wijst naar het opgegeven object, of converteert ruwe pointer naar [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopieer-constructeert [SmartPtr](../../system/smartptr/) object. Beide pointers wijzen daarna naar hetzelfde object. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopieer-constructeert [SmartPtr](../../system/smartptr/) object. Beide pointers wijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Verplaats-constructeert [SmartPtr](../../system/smartptr/) object. Werkt in feite twee pointers om, als ze beide dezelfde modus hebben. x kan onbruikbaar worden na de aanroep. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converteert het type van een gerefereerde array door een nieuwe array van een ander type te maken. Handig als er in C# een arraytypecast bestaat die niet wordt ondersteund in C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialiseert lege array. Wordt gebruikt om enkele C# codeconstructies te vertalen. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construeert een [SmartPtr](../../system/smartptr/) die eigendomsinformatie deelt met de initiële waarde van ptr, maar een niet-gerelateerde en onbeheerde pointer p bevat. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Zet pointer om naar een ander type met static_cast op het gepointeerde object. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converteert elk pointertype naar een pointer naar [Object](../../system/object/). Vereist niet dat het Pointee_ type volledig is. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Snelkoppeling om [System::TypeInfo](../../system/typeinfo/) object te krijgen voor het Pointee_ type. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Vernietigt [SmartPtr](../../system/smartptr/) object. Indien nodig, verlaagt de referentieteller van het gepointeerde object en verwijdert het object. |

## Zie ook

* Klasse [SmartPtr](../../system/smartptr/)
* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)