---
title: HashSetPtr
second_title: Aspose.Slides för C++ API-referens
description: Pekare för att behålla HashSet-referenser. Denna typ är en pekare för att hantera en annan objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.
type: docs
weight: 235
url: /sv/system.collections.generic/hashsetptr/
---
## HashSetPtr klass


Pekare för att behålla [HashSet](../hashset/) referenser. Denna typ är en pekare för att hantera en annan objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## Metoder

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Åtkomstfunktion för [begin()](../../system/smartptr/begin/)-metoden i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [begin()](../../system/smartptr/begin/)-metoden. |
| auto [begin](../../system/smartptr/begin/)() const | Åtkomstfunktion för [begin()](../../system/smartptr/begin/)-metoden i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [begin()](../../system/smartptr/begin/)-metoden. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till dess egen typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till basklass med static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till härledd typ med dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till härledd typ med dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Åtkomstfunktion för [cbegin()](../../system/smartptr/cbegin/)-metoden i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [cbegin()](../../system/smartptr/cbegin/)-metoden. |
| auto [cend](../../system/smartptr/cend/)() const | Åtkomstfunktion för [cend()](../../system/smartptr/cend/)-metoden i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [cend()](../../system/smartptr/cend/)-metoden. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Kastar pekaren till annan typ med const_cast på pekat objekt. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Kastar pekaren till annan typ med dynamic_cast på pekat objekt. |
| auto [end](../../system/smartptr/end/)() | Åtkomstfunktion för [end()](../../system/smartptr/end/)-metoden i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [end()](../../system/smartptr/end/)-metoden. |
| auto [end](../../system/smartptr/end/)() const | Åtkomstfunktion för [end()](../../system/smartptr/end/)-metoden i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [end()](../../system/smartptr/end/)-metoden. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Hämtar pekat objekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Hämtar pekarläge. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Hämtar pekat objekt, men påstår att pekaren är i delat läge. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Hämtar antalet delade pekare som finns till refererat objekt, inklusive den aktuella. Påstår att den aktuella pekaren är i delat läge. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Anropar [GetHashCode()](../../system/smartptr/gethashcode/) på pekat objekt. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Hämtar för närvarande refererat objekt (om någon) eller kastar ett undantag. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Hämtar refererat objekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
|  [HashSetPtr](./hashsetptr/)() | Konstruktor för nullpekare. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | Kopieringskonstruktor. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om pekat objekt är av en specifik typ eller dess subtyp. Följer C#-'is'-semantik. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Kontrollerar om pekaren pekar på ett annat objekt än det ägda (skapad av en aliaskonstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Kontrollerar om pekaren är i delat läge. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Kontrollerar om pekaren är i svagt läge. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Kontrollerar om pekaren inte är null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Kontrollerar om pekaren är null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Hämtar referens till pekat objekt. Påstår att pekaren inte är null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Tillåter åtkomst till medlemmar i refererat objekt. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Tillhandahåller mindre-än-jämförelse för [SmartPtr](../../system/smartptr/)-klassen. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Tillhandahåller mindre-än-jämförelse för [SmartPtr](../../system/smartptr/)-klassen. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Flytttilldelar [SmartPtr](../../system/smartptr/)-objektet. x blir oanvändbart. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopietilldelar [SmartPtr](../../system/smartptr/)-objektet. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopietilldelar [SmartPtr](../../system/smartptr/)-objektet. Utför nödvändiga typkonverteringar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Tilldelar råpekare till [SmartPtr](../../system/smartptr/)-objektet. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Sätter pekarvärde till nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om pekaren pekar på nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Tar bort aliasing (skapad av en aliaskonstruktor) från pekaren, ser till att den hanterar (om delad) eller spårar (om svag) samma objekt som den pekar på. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Sätter pekat objekt. |
| void [reset](../../system/smartptr/reset/)() | Gör så att pekaren pekar på nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Sätter pekarläge. Kan ändra referensräkningar för det refererade objektet. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Anropar SetTemplateWeakPtr()-metoden på pekat objekt (om något). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Skapar null-pekare [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/) som pekar på specificerat objekt, eller konverterar råpekare till [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopierar [SmartPtr](../../system/smartptr/)-objektet. Båda pekarna pekar på samma objekt efteråt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopierar [SmartPtr](../../system/smartptr/)-objektet. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om det är tillåtet. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Flyttkonstruktar [SmartPtr](../../system/smartptr/)-objektet. I praktiken byter två pekare plats, om de har samma läge. x kan vara oanvändbart efter anropet. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konverterar typen av refererad array genom att skapa en ny array av annan typ. Användbart om det finns en array-typkonvertering i C# som inte stöds i C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initierar tom array. Används för att översätta vissa C#-kodkonstruktioner. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruerar en [SmartPtr](../../system/smartptr/) som delar ägandinformation med det ursprungliga värdet av ptr, men har en orelaterad och ohanterad pekare p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Kastar pekaren till annan typ med static_cast på pekat objekt. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konverterar vilken pekartyp som helst till pekare på [Object](../../system/object/). Kräver inte att Pointee_-typen är komplett. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Genväg för att hämta [System::TypeInfo](../../system/typeinfo/)-objekt för Pointee_-typen. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Förstör [SmartPtr](../../system/smartptr/)-objektet. Vid behov minskar referen räknaren för pekat objekt och raderar objektet. |

## Se även

* Klass [SmartPtr](../../system/smartptr/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)