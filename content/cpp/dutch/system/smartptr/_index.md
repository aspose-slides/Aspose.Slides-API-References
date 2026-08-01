---
title: SmartPtr
second_title: Aspose.Slides voor C++ API-referentie
description: "Pointerklasse om types die op de heap worden gealloceerd te omsluiten. Gebruik deze om geheugen te beheren voor klassen die Object erven. Dit pointertype volgt intrusieve pointersemantiek. De referentieteller wordt opgeslagen in Object zelf of in een tellerstructuur die nauw verbonden is met de Object-instantie. In elk geval vormen alle SmartPtr-instanties een enkele eigendomsgroep, ongeacht hoe ze zijn aangemaakt, wat verschilt van hoe de std::shared_ptr-klasse zich gedraagt. Een ruwe pointer naar SmartPtr converteren is veilig zolang er andere SmartPtr-instanties bestaan die gedeelde referenties naar hetzelfde object houden. Een SmartPtr-klasse-instantie kan zich in één van twee toestanden bevinden: gedeelde pointer en zwakke pointer. Om het object levend te houden, moet het aantal gedeelde referenties positief zijn. Zowel zwakke als gedeelde pointers kunnen worden gebruikt om het gepointeerde object te benaderen (om methoden aan te roepen, velden te lezen of te schrijven, enz.), maar zwakke pointers dragen niet bij aan het referentietellen van gedeelde pointers. Het Object wordt verwijderd wanneer de laatste ‘shared’ SmartPtr-pointer naar het object wordt vernietigd. Zorg er dus voor dat dit niet gebeurt wanneer er geen andere gedeelde SmartPtr-pointers naar het object bestaan, bijvoorbeeld tijdens de constructie of vernietiging van het object. Gebruik System::Object::ThisProtector-bewakingsobjecten (in C++-code) of CppCTORSelfReference- of CppSelfReference-attribuut (in C#-code die wordt vertaald) om dit probleem op te lossen. Zorg ervoor dat lussreferenties worden verbroken door de System::WeakPtr-pointerklasse of System::SmartPtrMode::Weak-pointermodus (in C++-code) of CppWeakPtr-attribuut (in C#-code die wordt vertaald) te gebruiken. Als twee of meer objecten elkaar via ‘shared’ pointers refereren, worden ze nooit verwijderd. Als het pointertype (zwak of gedeeld) tijdens runtime moet worden gewijzigd, gebruik dan de System::SmartPtr<T>::set_Mode()-methode of de System::DynamicWeakPtr-klasse. De SmartPtr-klasse bevat geen virtuele methoden. U moet ervan alleen erven als u een eigen geheugenbeheersstrategie wilt creëren. Dit type is een pointer om de verwijdering van een ander object te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde, hetzij per const-referentie."
type: docs
weight: 1236
url: /nl/system/smartptr/
---
## SmartPtr klasse

Pointerklasse om types die op de heap worden toegewezen te omsluiten. Gebruik deze om geheugen te beheren voor klassen die [Object](../object/) erven. Dit pointertype volgt intrusieve pointersemantiek. De referentieteller wordt opgeslagen in [Object](../object/) zelf of in een tellerstructuur die nauw verbonden is met de [Object](../object/)-instantie. In elk geval vormen alle [SmartPtr](./)-instanties een enkele eigendomsgroep, ongeacht hoe ze zijn aangemaakt, wat verschilt van hoe de std::shared_ptr-klasse zich gedraagt. Een ruwe pointer naar [SmartPtr](./) converteren is veilig zolang er andere [SmartPtr](./)-instanties bestaan die gedeelde referenties naar hetzelfde object houden. [SmartPtr](./)-klasse-instantie kan zich in één van twee toestanden bevinden: gedeelde pointer en zwakke pointer. Om het object levend te houden, moet het aantal gedeelde referenties erop positief zijn. Zowel zwakke als gedeelde pointers kunnen worden gebruikt om het gepointeerde object te benaderen (om methoden aan te roepen, velden te lezen of te schrijven, enz.), maar zwakke pointers dragen niet bij aan het referentietellen van gedeelde pointers. [Object](../object/) wordt verwijderd wanneer de laatste ‘shared’ [SmartPtr](./)-pointer naar het object wordt vernietigd. Zorg er dus voor dat dit niet gebeurt wanneer er geen andere gedeelde [SmartPtr](./)-pointers naar het object bestaan, bijv. tijdens de constructie of vernietiging van het object. Gebruik System::Object::ThisProtector-bewakingsobjecten (in C++-code) of CppCTORSelfReference- of CppSelfReference-attribuut (in de te vertalen C#-code) om dit probleem op te lossen. Zorg er daarnaast voor dat lussreferenties worden verbroken door de [System::WeakPtr](../weakptr/)-pointerklasse of [System::SmartPtrMode::Weak](../smartptrmode/)-pointermodus (in C++-code) of CppWeakPtr-attribuut (in de te vertalen C#-code) te gebruiken. Als twee of meer objecten elkaar via ‘shared’-pointers refereren, worden ze nooit verwijderd. Als het pointertype (zwak of gedeeld) tijdens runtime moet worden gewijzigd, gebruik dan de [System::SmartPtr<T>::set_Mode()](./set_mode/)-methode of [System::DynamicWeakPtr](../dynamicweakptr/)-klasse. [SmartPtr](./)-klasse bevat geen virtuele methoden. U moet er alleen van erven als u een eigen geheugenbeheerstrategie wilt maken. Dit type is een pointer om de verwijdering van een ander object te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde, hetzij per const-referentie.

```cpp
template<class T>class SmartPtr
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type of the pointed object. Must be either [System::Object](../object/) or subclass of it. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| auto [begin](./begin/)() | Toegangsmethode voor [begin()](./begin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](./begin/) methode. |
| auto [begin](./begin/)() const | Toegangsmethode voor [begin()](./begin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](./begin/) methode. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Cast de pointer naar zijn eigen type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Cast de pointer naar basistype met static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Cast de pointer naar afgeleid type met dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Cast de pointer naar afgeleid type met dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Toegangsmethode voor [cbegin()](./cbegin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cbegin()](./cbegin/) methode. |
| auto [cend](./cend/)() const | Toegangsmethode voor [cend()](./cend/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cend()](./cend/) methode. |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Cast de pointer naar een ander type met const_cast op het gepointeerde object. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Cast de pointer naar een ander type met dynamic_cast op het gepointeerde object. |
| auto [end](./end/)() | Toegangsmethode voor [end()](./end/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](./end/) methode. |
| auto [end](./end/)() const | Toegangsmethode voor [end()](./end/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](./end/) methode. |
| [Pointee_](./pointee_/) * [get](./get/)() const | Geeft het gepointerde object. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Geeft de pointermodus. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Geeft het gepointerde object, maar stelt vast dat de pointer in gedeelde modus is. |
| int [get_shared_count](./get_shared_count/)() const | Geeft het aantal gedeelde pointers naar het gerefereerde object, inclusief de huidige. Stelt vast dat de huidige pointer in gedeelde modus is. |
| int [GetHashCode](./gethashcode/)() const | Roept [GetHashCode()](./gethashcode/) aan op het gepointerde object. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Geeft het momenteel gerefereerde object (indien aanwezig) of gooit een uitzondering. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Geeft het gepointerde object (indien aanwezig) of nullptr. Hetzelfde als [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Geeft het gerefereerde object. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Geeft het gepointerde object (indien aanwezig) of nullptr. Hetzelfde als [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Controleert of het gepointerde object van een specifiek type of een afgeleid type is. Volgt de C# ‘is’-semantiek. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Controleert of de pointer naar een ander object wijst dan het eigendom (gemaakt door een alias-constructor). |
| **bool** [IsShared](./isshared/)() const | Controleert of de pointer zich in gedeelde modus bevindt. |
| **bool** [IsWeak](./isweak/)() const | Controleert of de pointer zich in zwakke modus bevindt. |
| explicit  [operator bool](./operator_bool/)() const | Controleert of de pointer niet null is. |
| **bool** [operator!](./operator_not/)() const | Controleert of de pointer null is. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Geeft een referentie naar het gepointerde object. Stelt vast dat de pointer niet null is. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Staat toe leden van het gerefereerde object te benaderen. |
| **bool** [operator<](./operator_less/)(Y *) const | Biedt minder-vergelijkingssemantiek voor de [SmartPtr](./)-klasse. |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Biedt minder-vergelijkingssemantiek voor de [SmartPtr](./)-klasse. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Voert een move-assign toe aan een [SmartPtr](./)-object. x wordt onbruikbaar. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Voert een copy-assign toe aan een [SmartPtr](./)-object. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Voert een copy-assign toe aan een [SmartPtr](./)-object. Voert de vereiste typeconversies uit. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Wijs een ruwe pointer toe aan een [SmartPtr](./)-object. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Stelt de pointerwaarde in op nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Controleert of de pointer naar nullptr wijst. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Verwijdert aliasing (gecreëerd door een alias-constructor) van de pointer, en zorgt ervoor dat deze (indien gedeeld) of volgt (indien zwak) hetzelfde object waarnaar hij wijst. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Stelt het gepointerde object in. |
| void [reset](./reset/)() | Laat de pointer naar nullptr wijzen. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Stelt de pointermodus in. Kan de referentietellingen van het gerefereerde object wijzigen. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Roept SetTemplateWeakPtr() aan op het gepointerde object (indien aanwezig). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Maakt een [SmartPtr](./)-object aan van de vereiste modus. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Maakt een null-pointer [SmartPtr](./)-object aan van de vereiste modus. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Maakt een [SmartPtr](./) aan die naar het opgegeven object wijst, of converteert een ruwe pointer naar [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Construeert een kopie van een [SmartPtr](./)-object. Beide pointers wijzen daarna naar hetzelfde object. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Construeert een kopie van een [SmartPtr](./)-object. Beide pointers wijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Construeert een move-versie van een [SmartPtr](./)-object. Effectief wisselt het twee pointers uit, als beide dezelfde modus hebben. x kan na de aanroep onbruikbaar zijn. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converteert het type van de gerefereerde array door een nieuwe array van een ander type te creëren. Nuttig wanneer er in C# een array-type-cast bestaat die niet wordt ondersteund in C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Initialiseert een lege array. Wordt gebruikt om enkele C#-codeconstructies te vertalen. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Construeert een [SmartPtr](./) die eigendomsinformatie deelt met de initiële waarde van ptr, maar een niet-gerelateerde en onbeheerde pointer p bevat. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Cast de pointer naar een ander type met static_cast op het gepointerde object. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Converteert elk pointertype naar een pointer naar [Object](../object/). Vereist niet dat het Pointee_-type volledig is. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Snelkoppeling om een [System::TypeInfo](../typeinfo/)-object te verkrijgen voor het Pointee_-type. |
|  [~SmartPtr](./~smartptr/)() | Vernietigt het [SmartPtr](./)-object. Verlaagt indien nodig de referentieteller van het gepointerde object en verwijdert het. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Pointee_](./pointee_/) | Gepointerd type. |
| [SmartPtr_](./smartptr_/) | Gespecialiseerd smart-pointertype. |
| [ArrayType](./arraytype/) | Hetzelfde als Pointee_, als dat een specialisatie is van [System::Array](../array/), anders void. |
| [ValueType](./valuetype/) | Opslagtype van de gepointerde array. Alleen relevant als T een specialisatie is van [System::Array](../array/). |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)