---
title: X509ExtensionCollectionPtr
second_title: Aspose.Slides voor C++ API-referentie
description: Pointer naar verzameling van X509-extensies. Dit type is een pointer om de verwijdering van een ander object te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde, hetzij per const-referentie.
type: docs
weight: 170
url: /nl/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr klasse


Pointer naar verzameling van X509-extensies. Dit type is een pointer om de verwijdering van een ander object te beheren. Het moet op de stack worden gealloceerd en aan functies worden doorgegeven, hetzij per waarde, hetzij per const-referentie.

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## Methods

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accessor voor [begin()](../../system/smartptr/begin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../../system/smartptr/begin/) methode. |
| auto [begin](../../system/smartptr/begin/)() const | Accessor voor [begin()](../../system/smartptr/begin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](../../system/smartptr/begin/) methode. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Zet pointer om naar zijn eigen type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Zet pointer om naar basistype met static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Zet pointer om naar afgeleid type met dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Zet pointer om naar afgeleid type met dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accessor voor [cbegin()](../../system/smartptr/cbegin/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cbegin()](../../system/smartptr/cbegin/) methode. |
| auto [cend](../../system/smartptr/cend/)() const | Accessor voor [cend()](../../system/smartptr/cend/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [cend()](../../system/smartptr/cend/) methode. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Zet pointer om naar een ander type met const_cast op het aangestuurde object. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Zet pointer om naar een ander type met dynamic_cast op het aangestuurde object. |
| auto [end](../../system/smartptr/end/)() | Accessor voor [end()](../../system/smartptr/end/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../../system/smartptr/end/) methode. |
| auto [end](../../system/smartptr/end/)() const | Accessor voor [end()](../../system/smartptr/end/) methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [end()](../../system/smartptr/end/) methode. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Haalt het aangewezen object op. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Haalt pointermodus op. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Haalt het aangewezen object op, maar assert dat de pointer in gedeelde modus is. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Haalt het aantal gedeelde pointers op dat bestaat naar het verwezen object, inclusief de huidige. Assert dat de huidige pointer in gedeelde modus is. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Roept [GetHashCode()](../../system/smartptr/gethashcode/) aan op het aangewezen object. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Haalt het momenteel verwezen object op (indien aanwezig) of gooit een uitzondering. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Haalt het aangewezen object op (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Haalt het verwezen object op. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Haalt het aangewezen object op (indien aanwezig) of nullptr. Hetzelfde als [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Controleert of het aangewezen object van een specifiek type is of van een afgeleid type. Volgt de C# 'is' semantiek. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Controleert of de pointer naar een ander object wijst dan het bezit (aangemaakt door een aliasing constructor). |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Controleert of de pointer in gedeelde modus is. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Controleert of de pointer in zwakke modus is. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Controleert of de pointer niet null is. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Controleert of de pointer null is. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Haalt een referentie op naar het aangewezen object. Assert dat de pointer niet null is. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Staat toe leden van het verwezen object te benaderen. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Biedt minder-vergelijkingssemantiek voor de [SmartPtr](../../system/smartptr/)-klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Biedt minder-vergelijkingssemantiek voor de [SmartPtr](../../system/smartptr/)-klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Voert move-toewijzing uit op [SmartPtr](../../system/smartptr/) object. x wordt onbruikbaar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Voert copy-toewijzing uit op [SmartPtr](../../system/smartptr/) object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Voert copy-toewijzing uit op [SmartPtr](../../system/smartptr/) object. Voert benodigde typeconversies uit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Wijst een ruwe pointer toe aan [SmartPtr](../../system/smartptr/) object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Stelt pointerwaarde in op nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Controleert of de pointer naar nullptr wijst. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | Toegangsfunctie. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Verwijdert aliasing (aangemaakt door een aliasing constructor) van de pointer, zorgt ervoor dat deze (indien gedeeld) beheert of (indien zwak) volgt hetzelfde object waarnaar hij wijst. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Stelt het aangewezen object in. |
| void [reset](../../system/smartptr/reset/)() | Laat de pointer naar nullptr wijzen. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Stelt pointermodus in. Kan referentietellingen van het verwezen object wijzigen. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Roept SetTemplateWeakPtr() methode aan op het aangewezen object (indien aanwezig). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Creëert een [SmartPtr](../../system/smartptr/) object van de vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Creëert een null-pointer [SmartPtr](../../system/smartptr/) object van de vereiste modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Creëert een [SmartPtr](../../system/smartptr/) die wijst naar het gespecificeerde object, of converteert een ruwe pointer naar [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Voert copy-constructie uit van [SmartPtr](../../system/smartptr/) object. Beide pointers wijzen daarna naar hetzelfde object. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Voert copy-constructie uit van [SmartPtr](../../system/smartptr/) object. Beide pointers wijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Voert move-constructie uit van [SmartPtr](../../system/smartptr/) object. Werkt in feite twee pointers om, mits ze dezelfde modus hebben. x kan na de oproep onbruikbaar zijn. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converteert het type van een verwezen array door een nieuwe array van een ander type te maken. Nuttig als er in C# een arraytypecast is die niet ondersteund wordt in C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialiseert een lege array. Wordt gebruikt om enkele C# codeconstructies te vertalen. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construeert een [SmartPtr](../../system/smartptr/) die eigendomsinformatie deelt met de initiële waarde van ptr, maar een niet-gerelateerd en onbeheerd pointer p bevat. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Zet pointer om naar een ander type met static_cast op het aangewezen object. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converteert elk pointertype naar een pointer naar [Object](../../system/object/). Vereist niet dat het Pointee_ type compleet is. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Snelkoppeling om het [System::TypeInfo](../../system/typeinfo/) object voor het Pointee_ type te krijgen. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | Constructor voor null-pointer. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | Constructor. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Vernietigt [SmartPtr](../../system/smartptr/) object. Vermindert indien nodig de referentieteller van het aangewezen object en verwijdert het object. |
## Zie ook

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.Slides](../../)