---
title: QueuePtr
second_title: Aspose.Slides för C++ API-referens
description: Köpekare. Denna typ är en pekare för att hantera raderingen av andra objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.
type: docs
weight: 482
url: /sv/system.collections.generic/queueptr/
---
## QueuePtr klass

[Queue](../queue/) pekare. Den här typen är en pekare för att hantera andra objekts radering. Den bör allokeras på stacken och passeras till funktioner antingen som värde eller som konstant referens.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Åtkomstfunktion för [begin()](../../system/smartptr/begin/) metod i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [begin()](../../system/smartptr/begin/) metod. |
| auto [begin](../../system/smartptr/begin/)() const | Åtkomstfunktion för [begin()](../../system/smartptr/begin/) metod i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [begin()](../../system/smartptr/begin/) metod. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Konverterar pekare till dess egen typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Konverterar pekare till basklass med static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Konverterar pekare till avledd typ med dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Konverterar pekare till avledd typ med dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Åtkomstfunktion för [cbegin()](../../system/smartptr/cbegin/) metod i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [cbegin()](../../system/smartptr/cbegin/) metod. |
| auto [cend](../../system/smartptr/cend/)() const | Åtkomstfunktion för [cend()](../../system/smartptr/cend/) metod i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [cend()](../../system/smartptr/cend/) metod. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Konverterar pekare till annan typ med const_cast på det pekade objektet. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Konverterar pekare till annan typ med dynamic_cast på det pekade objektet. |
| auto [end](../../system/smartptr/end/)() | Åtkomstfunktion för [end()](../../system/smartptr/end/) metod i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [end()](../../system/smartptr/end/) metod. |
| auto [end](../../system/smartptr/end/)() const | Åtkomstfunktion för [end()](../../system/smartptr/end/) metod i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [end()](../../system/smartptr/end/) metod. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Hämtar pekat objekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Hämtar pekarläge. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Hämtar pekat objekt, men påstår att pekaren är i delat läge. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Hämtar antalet delade pekare som finns på det refererade objektet, inklusive den nuvarande. Påstår att den aktuella pekaren är i delat läge. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Anropar [GetHashCode()](../../system/smartptr/gethashcode/) på det pekade objektet. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Hämtar för närvarande refererat objekt (om något) eller kastar ett undantag. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Hämtar refererat objekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Hämtar pekat objekt (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om det pekade objektet är av en specifik typ eller dess subtyp. Följer C#-semantiken för 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Kontrollerar om pekaren pekar på ett annat objekt än det ägda (skapat av en alias-konstruktör). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Kontrollerar om pekaren är i delat läge. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Kontrollerar om pekaren är i svagt läge. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Kontrollerar om pekaren inte är null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Kontrollerar om pekaren är null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Hämtar referens till pekat objekt. Påstår att pekaren inte är null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Tillåter åtkomst till medlemmar i det refererade objektet. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](../../system/smartptr/)-klassen. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](../../system/smartptr/)-klassen. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Flytt-tilldelar [SmartPtr](../../system/smartptr/)-objekt. x blir oanvändbart. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopierar-tilldelar [SmartPtr](../../system/smartptr/)-objekt. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopierar-tilldelar [SmartPtr](../../system/smartptr/)-objekt. Gör nödvändiga typkonverteringar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Tilldelar råpekare till [SmartPtr](../../system/smartptr/)-objekt. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Sätter pekarvärdet till nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om pekaren pekar på nullptr. |
|  [QueuePtr](./queueptr/)() | Skapar null-pekare. |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | Skapar pekare till en specifik kö. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Tar bort alias-ning (skapat av en alias-konstruktör) från pekaren, säkerställer att den hanterar (om delad) eller spårar (om svag) samma objekt som den pekar på. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Sätter pekat objekt. |
| void [reset](../../system/smartptr/reset/)() | Får pekaren att peka på nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Sätter pekarläge. Kan ändra referensräkningar för det refererade objektet. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Anropar SetTemplateWeakPtr()-metoden på det pekade objektet (om något). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Skapar null-pekar-[SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/) som pekar på angivet objekt, eller konverterar råpekare till [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiekonstruerar [SmartPtr](../../system/smartptr/)-objekt. Båda pekarna pekar på samma objekt efteråt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiekonstruerar [SmartPtr](../../system/smartptr/)-objekt. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om tillåtet. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Flytt-konstruerar [SmartPtr](../../system/smartptr/)-objekt. Byter i praktiken två pekare om de har samma läge. x kan bli oanvändbart efter anrop. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konverterar typ av refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en array-typ-cast som inte stöds i C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initierar tom array. Används för att översätta vissa C#-kodkonstruktioner. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruerar en [SmartPtr](../../system/smartptr/) som delar ägandinformations med det ursprungliga värdet av ptr, men håller en orelaterad och ohanterad pekare p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Konverterar pekare till annan typ med static_cast på det pekade objektet. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konverterar vilken pekartyp som helst till pekare till [Object](../../system/object/). Kräver inte att Pointee_-typen är komplett. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Genväg för att hämta [System::TypeInfo](../../system/typeinfo/)-objekt för Pointee_-typen. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Förstör [SmartPtr](../../system/smartptr/)-objekt. Vid behov minskar den pekade objektets referensräknare och tar bort objektet. |

## Se också

* Klass [SmartPtr](../../system/smartptr/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)