---
title: ListPtr
second_title: Aspose.Slides för C++ API-referens
description: Listpekare med åtkomstoperatorer. Denna typ är en pekare för att hantera borttagning av andra objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.
type: docs
weight: 456
url: /sv/system.collections.generic/listptr/
---
## ListPtr klass

[List](../list/) pekare med åtkomstoperatorer. Denna typ är en pekare för att hantera borttagning av andra objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Åtkomstmetod för [begin()](../../system/smartptr/begin/)-metod i en underliggande samling. Kompilerar endast om SmartPtr_ är specialiseringstyp med [begin()](../../system/smartptr/begin/)-metod. |
| auto [begin](../../system/smartptr/begin/)() const | Åtkomstmetod för [begin()](../../system/smartptr/begin/)-metod i en underliggande samling. Kompilerar endast om SmartPtr_ är specialiseringstyp med [begin()](../../system/smartptr/begin/)-metod. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till dess egen typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till basklass med static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till avledd typ med dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till avledd typ med dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Åtkomstmetod för [cbegin()](../../system/smartptr/cbegin/)-metod i en underliggande samling. Kompilerar endast om SmartPtr_ är specialiseringstyp med [cbegin()](../../system/smartptr/cbegin/)-metod. |
| auto [cend](../../system/smartptr/cend/)() const | Åtkomstmetod för [cend()](../../system/smartptr/cend/)-metod i en underliggande samling. Kompilerar endast om SmartPtr_ är specialiseringstyp med [cend()](../../system/smartptr/cend/)-metod. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Kastar pekaren till en annan typ med const_cast på pekat objekt. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Kastar pekaren till en annan typ med dynamic_cast på pekat objekt. |
| auto [end](../../system/smartptr/end/)() | Åtkomstmetod för [end()](../../system/smartptr/end/)-metod i en underliggande samling. Kompilerar endast om SmartPtr_ är specialiseringstyp med [end()](../../system/smartptr/end/)-metod. |
| auto [end](../../system/smartptr/end/)() const | Åtkomstmetod för [end()](../../system/smartptr/end/)-metod i en underliggande samling. Kompilerar endast om SmartPtr_ är specialiseringstyp med [end()](../../system/smartptr/end/)-metod. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Hämtar pekat objekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Hämtar pekarläge. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Hämtar pekat objekt, men påstår att pekaren är i delat läge. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Hämtar antal delade pekare som finns på refererat objekt, inklusive den aktuella. Påstår att den aktuella pekaren är i delat läge. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Anropar [GetHashCode()](../../system/smartptr/gethashcode/) på pekat objekt. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Hämtar för närvarande refererat objekt (om något) eller kastar ett undantag. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Hämtar refererat objekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om pekat objekt är av en specifik typ eller dess underliggande typ. Följer C#-semantiken för 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Kontrollerar om pekaren pekar på ett annat objekt än det ägda (skapat av en alias-konstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Kontrollerar om pekaren är i delat läge. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Kontrollerar om pekaren är i svagt läge. |
|  [ListPtr](./listptr/)(std::nullptr_t) | Initierar null-pekare. |
|  [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | Initierar pekare till angiven lista. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Kontrollerar om pekaren inte är null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Kontrollerar om pekaren är null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Hämtar referens till pekat objekt. Påstår att pekaren inte är null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Tillåter åtkomst till medlemmar i det refererade objektet. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](../../system/smartptr/)-klassen. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](../../system/smartptr/)-klassen. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Flytttilldelar [SmartPtr](../../system/smartptr/)-objekt. x blir oanvändbart. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiatilldelar [SmartPtr](../../system/smartptr/)-objekt. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiatilldelar [SmartPtr](../../system/smartptr/)-objekt. Gör nödvändiga typkonverteringar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Tilldelar rå pekare till [SmartPtr](../../system/smartptr/)-objekt. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Sätter pekarvärde till nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om [List](../list/)-pekare är null. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | Åtkomstmetod. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | Åtkomstmetod. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Tar bort aliasing (skapad av en alias-konstruktor) från pekare, säkerställer att den hanterar (om delad) eller spårar (om svag) samma objekt den pekar på. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Sätter pekat objekt. |
| void [reset](../../system/smartptr/reset/)() | Gör så att pekaren pekar på nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Sätter pekarläge. Kan ändra referensräkningar för det refererade objektet. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Anropar SetTemplateWeakPtr()-metoden på pekat objekt (om något). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Skapar null-pekare [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/) som pekar på angivet objekt, eller konverterar rå pekare till [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopierar konstruerar [SmartPtr](../../system/smartptr/)-objekt. Båda pekarna pekar sedan på samma objekt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopierar konstruerar [SmartPtr](../../system/smartptr/)-objekt. Båda pekarna pekar sedan på samma objekt. Utför typkonvertering om tillåtet. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Flyttkonstruerar [SmartPtr](../../system/smartptr/)-objekt. Byter i praktiken två pekare om de har samma läge. x kan bli oanvändbart efter anropet. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konverterar typ av refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en array-typcast som inte stöds i C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initierar tom array. Används för att översätta vissa C#-kodkonstruktioner. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstrukterar en [SmartPtr](../../system/smartptr/) som delar ägandinformations med det ursprungliga värdet av ptr, men håller en orelaterad och ohanterad pekare p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Kastar pekaren till en annan typ med static_cast på pekat objekt. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konverterar vilken pekartyp som helst till pekare till [Object](../../system/object/). Kräver inte att Pointee_-typen är komplett. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Genväg för att få [System::TypeInfo](../../system/typeinfo/)-objekt för Pointee_-typen. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Förstör [SmartPtr](../../system/smartptr/)-objekt. Om nödvändigt minskar referensräknaren för pekat objekt och raderar objektet. |

## Se även

* Klass [SmartPtr](../../system/smartptr/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)