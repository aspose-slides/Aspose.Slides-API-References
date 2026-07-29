---
title: WeakPtr
second_title: Aspose.Slides för C++ API-referens
description: "Underklass till System::SmartPtr som sätter sig själv i svagt läge vid konstruktion. Observera att denna klass inte garanterar att dess instans alltid förblir i svagt läge eftersom set_Mode() fortfarande är åtkomlig. Denna typ är en pekare för att hantera borttagning av andra objekt. Den bör allokeras på stacken och överlämnas till funktioner antingen som värde eller som konstant referens."
type: docs
weight: 1496
url: /sv/system/weakptr/
---
## WeakPtr klass


Subclass till [System::SmartPtr](../smartptr/) som sätter sig själv till svagt läge vid konstruktion. Observera att denna klass inte garanterar att dess instans alltid förblir i svagt läge eftersom [set_Mode()](../smartptr/set_mode/) fortfarande är åtkomlig. Denna typ är en pekare för att hantera andra objekts radering. Den bör allokeras på stacken och överlämnas till funktioner antingen som värde eller som konstant referens.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | Pointee type. |
## Metoder

| Method | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Åtkomstfunktion för [begin()](../smartptr/begin/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiseringstyp med [begin()](../smartptr/begin/)-metoden. |
| auto [begin](../smartptr/begin/)() const | Åtkomstfunktion för [begin()](../smartptr/begin/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiseringstyp med [begin()](../smartptr/begin/)-metoden. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Kastar pekaren till dess egen typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Kastar pekaren till basklass med static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Kastar pekaren till en avledd typ med dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Kastar pekaren till en avledd typ med dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Åtkomstfunktion för [cbegin()](../smartptr/cbegin/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiseringstyp med [cbegin()](../smartptr/cbegin/)-metoden. |
| auto [cend](../smartptr/cend/)() const | Åtkomstfunktion för [cend()](../smartptr/cend/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiseringstyp med [cend()](../smartptr/cend/)-metoden. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Kastar pekaren till en annan typ med const_cast på det pekade objektet. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Kastar pekaren till en annan typ med dynamic_cast på det pekade objektet. |
| auto [end](../smartptr/end/)() | Åtkomstfunktion för [end()](../smartptr/end/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiseringstyp med [end()](../smartptr/end/)-metoden. |
| auto [end](../smartptr/end/)() const | Åtkomstfunktion för [end()](../smartptr/end/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiseringstyp med [end()](../smartptr/end/)-metoden. |
| **bool** [expired](./expired/)() const | Kontrollerar om det refererade objektet redan har raderats. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Hämtar pekat objekt. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Hämtar pekarläget. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Hämtar pekat objekt, men påstår att pekaren är i delat läge. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Hämtar antalet delade pekare som finns till det refererade objektet, inklusive den aktuella. Påstår att den aktuella pekaren är i delat läge. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Hämtar det refererade objektet. Påstår att pekaren är i svagt läge. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Anropar [GetHashCode()](../smartptr/gethashcode/) på det pekade objektet. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Hämtar för närvarande refererat objekt (om något) eller kastar ett undantag. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Hämtar det refererade objektet. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Kontrollerar om pekat objekt är av en specifik typ eller dess underordnade typ. Följer C#-'is' semantik. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Kontrollerar om pekaren pekar på ett annat objekt än det som ägs (skapat av en aliaskonstruktör). |
| **bool** [IsShared](../smartptr/isshared/)() const | Kontrollerar om pekaren är i delat läge. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Kontrollerar om pekaren är i svagt läge. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Kontrollerar om pekaren inte är null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Kontrollerar om pekaren är null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Hämtar referens till pekat objekt. Påstår att pekaren inte är null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Tillåter åtkomst till medlemmar i det refererade objektet. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Tillhandahåller mindre-jämförelsesemantik för [SmartPtr](../smartptr/)-klassen. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Tillhandahåller mindre-jämförelsesemantik för [SmartPtr](../smartptr/)-klassen. |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Tilldelar värde till svag pekare. Anropar den specifika tilldelningsoperatorn i SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Flytt-tilldelar [SmartPtr](../smartptr/)-objekt. x blir oanvändbart. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Kopierar och tilldelar [SmartPtr](../smartptr/)-objekt. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Kopierar och tilldelar [SmartPtr](../smartptr/)-objekt. Gör nödvändiga typkonverteringar. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Tilldelar råpekare till [SmartPtr](../smartptr/)-objekt. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Sätter pekarvärdet till nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om svag pekare är null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Tar bort aliasering (skapad av en aliaskonstruktör) från pekaren, säkerställer att den hanterar (om delad) eller spårar (om svag) samma objekt som den pekar på. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Sätter pekat objekt. |
| void [reset](../smartptr/reset/)() | Gör så att pekaren pekar på nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Sätter pekarläget. Kan förändra referensräkningar för det refererade objektet. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Anropar SetTemplateWeakPtr()-metoden på det pekade objektet (om något). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Skapar [SmartPtr](../smartptr/)-objekt av önskat läge. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Skapar null-pekare [SmartPtr](../smartptr/)-objekt av önskat läge. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Skapar [SmartPtr](../smartptr/) som pekar på specificerat objekt, eller konverterar råpekare till [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopierar konstruktion av [SmartPtr](../smartptr/)-objekt. Båda pekarna pekar på samma objekt efteråt. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopierar konstruktion av [SmartPtr](../smartptr/)-objekt. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om tillåtet. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Flyttkonstruktion av [SmartPtr](../smartptr/)-objekt. Byt effektivt två pekare om de har samma läge. x kan bli oanvändbart efter anropet. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Konverterar typ av refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en array-typkonvertering som inte stöds i C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Initierar tom array. Används för att översätta vissa C#-kodkonstruktioner. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruktion av en [SmartPtr](../smartptr/) som delar ägandesinformation med det ursprungliga värdet av ptr, men håller en orelaterad och icke-hanterad pekare p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Kastar pekaren till en annan typ med static_cast på det pekade objektet. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Konverterar vilken pekartyp som helst till pekare till [Object](../object/). Kräver inte att Pointee_-typen är komplett. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Genväg för att hämta [System::TypeInfo](../typeinfo/)-objekt för Pointee_-typen. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Skapar null-pekare. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Skapar svag pekare till angivet objekt. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Skapar svag pekare som refererar samma pekare som ptr pekar på. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Skapar svag pekare som refererar samma pekare som x pekar på. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Kopiekonstruktion av svag pekare. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Kopiekonstruktion av svag pekare. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Flyttkonstruktion av svag pekare. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Förstör [SmartPtr](../smartptr/)-objekt. Om nödvändigt minskar den pekade objektets referensräknare och tar bort objektet. |
## Typdefinitioner

| Typdefinition | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias för motsvarande [SmartPtr](../smartptr/)-klass. |
| [WeakPtr_](./weakptr_/) | Alias för egen typ. |
| [Pointee_](./pointee_/) | Pekartyp. |

## Se även

* Klass [SmartPtr](../smartptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)