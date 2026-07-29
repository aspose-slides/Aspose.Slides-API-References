---
title: StringCollectionPtr
second_title: Aspose.Slides för C++ API-referens
description: String-samling pekare med åtkomstoperator.
type: docs
weight: 40
url: /sv/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr klass

String-samling pekare med åtkomstoperator.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Åtkomstfunktion för [begin()](../../system/smartptr/begin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [begin()](../../system/smartptr/begin/)-metoden. |
| auto [begin](../../system/smartptr/begin/)() const | Åtkomstfunktion för [begin()](../../system/smartptr/begin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [begin()](../../system/smartptr/begin/)-metoden. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till sin egen typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till basklass med static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till avledd typ med dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till avledd typ med dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Åtkomstfunktion för [cbegin()](../../system/smartptr/cbegin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [cbegin()](../../system/smartptr/cbegin/)-metoden. |
| auto [cend](../../system/smartptr/cend/)() const | Åtkomstfunktion för [cend()](../../system/smartptr/cend/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [cend()](../../system/smartptr/cend/)-metoden. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Kastar pekaren till en annan typ med const_cast på det pekade objektet. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Kastar pekaren till en annan typ med dynamic_cast på det pekade objektet. |
| auto [end](../../system/smartptr/end/)() | Åtkomstfunktion för [end()](../../system/smartptr/end/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [end()](../../system/smartptr/end/)-metoden. |
| auto [end](../../system/smartptr/end/)() const | Åtkomstfunktion för [end()](../../system/smartptr/end/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [end()](../../system/smartptr/end/)-metoden. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Hämtar det pekade objektet. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Hämtar pekarläget. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Hämtar det pekade objektet, men påstår att pekaren är i delat läge. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Hämtar antalet delade pekare som existerar till refererat objekt, inklusive den aktuella. Påstår att den aktuella pekaren är i delat läge. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Anropar [GetHashCode()](../../system/smartptr/gethashcode/) på det pekade objektet. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Hämtar det för närvarande refererade objektet (om något) eller kastar ett undantag. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Hämtar det pekade objektet (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Hämtar det refererade objektet. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Hämtar det pekade objektet (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om det pekade objektet är av en specifik typ eller en barntyp. Följer C#-'is'-semantik. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Kontrollerar om pekaren pekar på ett annat objekt än det ägda (skapat av en alias-konstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Kontrollerar om pekaren är i delat läge. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Kontrollerar om pekaren är i svagt läge. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Kontrollerar om pekaren inte är null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Kontrollerar om pekaren är null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Hämtar referens till det pekade objektet. Påstår att pekaren inte är null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Tillåter åtkomst till medlemmar i det refererade objektet. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](../../system/smartptr/)-klassen. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](../../system/smartptr/)-klassen. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Flytt-tilldelar [SmartPtr](../../system/smartptr/)-objektet. x blir oanvändbar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopierar-tilldelar [SmartPtr](../../system/smartptr/)-objektet. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopierar-tilldelar [SmartPtr](../../system/smartptr/)-objektet. Gör nödvändiga typkonverteringar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Tilldelar råpekare till [SmartPtr](../../system/smartptr/)-objektet. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Sätter pekarvärdet till nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om pekaren pekar på nullptr. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | Åtkomstfunktion. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Tar bort aliasering (skapad av en alias-konstruktor) från pekaren, säkerställer att den hanterar (om delad) eller spårar (om svag) samma objekt som den pekar på. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Sätter det pekade objektet. |
| void [reset](../../system/smartptr/reset/)() | Gör pekaren pekande på nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Sätter pekarläget. Kan ändra referensräkningar på det refererade objektet. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Anropar SetTemplateWeakPtr()-metoden på det pekade objektet (om något). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Skapar null-pekare [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/) som pekar på angivet objekt, eller konverterar råpekare till [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopierar-konstruerar [SmartPtr](../../system/smartptr/)-objektet. Båda pekarna pekar på samma objekt efteråt. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopierar-konstruerar [SmartPtr](../../system/smartptr/)-objektet. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om tillåtet. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Flyttar-konstruerar [SmartPtr](../../system/smartptr/)-objektet. Byter i princip två pekare om de har samma läge. x kan bli oanvänd efter anropet. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konverterar typ av refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en array-typ-cast som inte stöds i C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initierar tom array. Används för att översätta vissa C#-konstrukt. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruerar en [SmartPtr](../../system/smartptr/) som delar ägandinformations med det ursprungliga ptr-värdet, men håller en orelaterad och ohanterad pekare p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Kastar pekaren till en annan typ med static_cast på det pekade objektet. |
| [StringCollectionPtr](./stringcollectionptr/)() | Konstruerar null-pekare. |
| [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | Konstruerar pekare till en specifik samling. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konverterar vilken pekartyp som helst till pekare till [Object](../../system/object/). Kräver inte att Pointee_-typen är komplett. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Genväg för att få [System::TypeInfo](../../system/typeinfo/)-objektet för Pointee_-typen. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Förstör [SmartPtr](../../system/smartptr/)-objektet. Om nödvändigt minskar den pekade objektets referensräknare och raderar objektet. |

## Se även

* Klass [SmartPtr](../../system/smartptr/)
* Namnutrymme [System::Collections::Specialized](../)
* Bibliotek [Aspose.Slides](../../)