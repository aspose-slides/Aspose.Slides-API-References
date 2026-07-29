---
title: DynamicWeakPtr
second_title: Aspose.Slides för C++ API-referens
description: Smart pekarklass som spårar pekarlägen för mallargumenten av det lagrade objektet och uppdaterar dem efter varje tilldelning. Denna typ är en pekare för att hantera raderingen av andra objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.
type: docs
weight: 781
url: /sv/system/dynamicweakptr/
---
## DynamicWeakPtr klass

Smart pointer class which tracks pointer modes of template arguments of stored object and updates them after each assignment. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Pointee | typ. |
| trunkMode | Läge för smartpekaren själv, delad eller svag. |
| weakLeafs | Index för mallargumenten av den lagrade typen som bör sättas till svagt pekarläge. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Åtkomstfunktion för [begin()](../smartptr/begin/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiserad typ med [begin()](../smartptr/begin/)-metoden. |
| auto [begin](../smartptr/begin/)() const | Åtkomstfunktion för [begin()](../smartptr/begin/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiserad typ med [begin()](../smartptr/begin/)-metoden. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Kastar pekaren till dess egen typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Kastar pekaren till basklassen med static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Kastar pekaren till en avledd typ med dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Kastar pekaren till en avledd typ med dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Åtkomstfunktion för [cbegin()](../smartptr/cbegin/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiserad typ med [cbegin()](../smartptr/cbegin/)-metoden. |
| auto [cend](../smartptr/cend/)() const | Åtkomstfunktion för [cend()](../smartptr/cend/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiserad typ med [cend()](../smartptr/cend/)-metoden. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Kastar pekaren till en annan typ med const_cast på det pekade objektet. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Kastar pekaren till en annan typ med dynamic_cast på det pekade objektet. |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Skapar en null smartpekare. |
| [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Skapar en smartpekare som pekar på det givna objektet. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Kopierar smartpekaren via copy-konstruktor. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Kopierar smartpekaren via copy-konstruktor. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Kopierar smartpekaren via copy-konstruktor. |
| [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Flyttar smartpekaren via move-konstruktor. |
| auto [end](../smartptr/end/)() | Åtkomstfunktion för [end()](../smartptr/end/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiserad typ med [end()](../smartptr/end/)-metoden. |
| auto [end](../smartptr/end/)() const | Åtkomstfunktion för [end()](../smartptr/end/)-metoden i en underliggande samling. Kompilerar bara om SmartPtr_ är en specialiserad typ med [end()](../smartptr/end/)-metoden. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Hämtar pekat objekt. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Hämtar pekarläge. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Hämtar pekat objekt, men påstår att pekaren är i delat läge. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Hämtar antalet delade pekare som finns till det refererade objektet, inklusive den aktuella. Påstår att den aktuella pekaren är i delat läge. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Anropar [GetHashCode()](../smartptr/gethashcode/) på det pekade objektet. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Hämtar för närvarande refererat objekt (om något) eller kastar ett undantag. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Hämtar refererat objekt. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Kontrollerar om det pekade objektet är av en specifik typ eller dess underliggande typ. Följer C#-'is'-semantik. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Kontrollerar om pekaren pekar på ett annat objekt än det som ägs (skapat av en alias-konstruktor). |
| **bool** [IsShared](../smartptr/isshared/)() const | Kontrollerar om pekaren är i delat läge. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Kontrollerar om pekaren är i svagt läge. |
| explicit [operator bool](../smartptr/operator_bool/)() const | Kontrollerar om pekaren inte är null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Kontrollerar om pekaren är null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Hämtar referens till det pekade objektet. Påstår att pekaren inte är null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Tillåter åtkomst till medlemmar i det refererade objektet. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](../smartptr/)-klassen. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](../smartptr/)-klassen. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Flytttilldelar smartpekare. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Kopierar tilldelning av smartpekare. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Kopierar tilldelning av smartpekare. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Tilldelar smartpekare. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Sätter smartpekare till null. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om smartpekaren är null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Tar bort aliasing (skapat av en alias-konstruktor) från pekaren, säkerställer att den hanterar (om delad) eller spårar (om svag) samma objekt som den pekar på. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Sätter pekat objekt. |
| void [reset](../smartptr/reset/)() | Gör så att pekaren pekar på nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Sätter pekarläge. Kan ändra referensräkningen för det refererade objektet. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Anropar SetTemplateWeakPtr()-metoden på det pekade objektet (om något). |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Skapar [SmartPtr](../smartptr/)-objekt av önskat läge. |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Skapar null-pekare [SmartPtr](../smartptr/)-objekt av önskat läge. |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Skapar [SmartPtr](../smartptr/) som pekar på specificerat objekt, eller konverterar råpekare till [SmartPtr](../smartptr/). |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopierar konstruerar [SmartPtr](../smartptr/)-objekt. Båda pekarna pekar på samma objekt efteråt. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopierar konstruerar [SmartPtr](../smartptr/)-objekt. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om tillåtet. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Flyttkonstruktor för [SmartPtr](../smartptr/)-objekt. Byter i praktiken två pekare om de har samma läge. x kan vara oanvändbar efter anropet. |
| explicit [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Konverterar typen för refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en array-typkonvertering som inte stöds i C++. |
| explicit [SmartPtr](../smartptr/smartptr/)(const Y\&) | Initierar en tom array. Används för att översätta vissa C#-kodkonstruktioner. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruerar en [SmartPtr](../smartptr/) som delar ägandainformation med det ursprungliga värdet av ptr, men håller en orelaterad och ohanterad pekare p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Kastar pekaren till en annan typ med static_cast på det pekade objektet. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Konverterar vilken pekartyp som helst till pekare till [Object](../object/). Kräver inte att Pointee_-typen är komplett. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Genväg för att få [System::TypeInfo](../typeinfo/)-objektet för Pointee_-typen. |
| [~SmartPtr](../smartptr/~smartptr/)() | Förstör [SmartPtr](../smartptr/)-objektet. Om nödvändigt minskar den pekade objektets referensräknare och raderar objektet. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) basisklass-alias. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Självtyp-alias. |
| [Pointee_](./pointee_/) | Pekartyp. |

## Se även

* Klass [SmartPtr](../smartptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)