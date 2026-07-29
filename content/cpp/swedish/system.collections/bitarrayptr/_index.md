---
title: BitArrayPtr
second_title: Aspose.Slides för C++ API-referens
description: Pekare till BitArray. Denna typ är en pekare för att hantera en annan objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.
type: docs
weight: 14
url: /sv/system.collections/bitarrayptr/
---
## BitArrayPtr klass


Pointer to [BitArray](../bitarray/). Denna typ är en pekare för att hantera annan objekts borttagning. Den bör allokeras på stack och skickas till funktioner antingen som värde eller som konstant referens.

```cpp
class BitArrayPtr : public System::SmartPtr<BitArray>
```

## Metoder

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accessör för [begin()](../../system/smartptr/begin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiserad typ med [begin()](../../system/smartptr/begin/)-metoden. |
| auto [begin](../../system/smartptr/begin/)() const | Accessör för [begin()](../../system/smartptr/begin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiserad typ med [begin()](../../system/smartptr/begin/)-metoden. |
|  [BitArrayPtr](./bitarrayptr/)() | Initierar nullpekare. |
|  [BitArrayPtr](./bitarrayptr/)(const [SharedPtr](../../system/sharedptr/)\<[BitArray](../bitarray/)\>\&) | Konverteringskonstruktor. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till dess egen typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till basklass med static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till en avledd typ med dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Kastar pekaren till en avledd typ med dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accessör för [cbegin()](../../system/smartptr/cbegin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiserad typ med [cbegin()](../../system/smartptr/cbegin/)-metoden. |
| auto [cend](../../system/smartptr/cend/)() const | Accessör för [cend()](../../system/smartptr/cend/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiserad typ med [cend()](../../system/smartptr/cend/)-metoden. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Kastar pekaren till en annan typ med const_cast på det pekade objektet. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Kastar pekaren till en annan typ med dynamic_cast på det pekade objektet. |
| auto [end](../../system/smartptr/end/)() | Accessör för [end()](../../system/smartptr/end/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiserad typ med [end()](../../system/smartptr/end/)-metoden. |
| auto [end](../../system/smartptr/end/)() const | Accessör för [end()](../../system/smartptr/end/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiserad typ med [end()](../../system/smartptr/end/)-metoden. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Hämtar det pekade objektet. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Hämtar pekarläget. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Hämtar det pekade objektet, men påstår att pekaren är i delat läge. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Hämtar antalet delade pekare som finns till det refererade objektet, inklusive den nuvarande. Påstår att den nuvarande pekaren är i delat läge. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Anropar [GetHashCode()](../../system/smartptr/gethashcode/) på det pekade objektet. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Hämtar det för närvarande refererade objektet (om något) eller kastar ett undantag. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Hämtar det pekade objektet (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Hämtar det refererade objektet. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Hämtar det pekade objektet (om något) eller nullptr. Samma som [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om det pekade objektet är av en specifik typ eller dess underklass. Följer C# 'is'-semantik. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Kontrollerar om pekaren pekar på ett annat objekt än det ägda (skapad av en alias-konstruktor). |
| **bool** [IsNull](./isnull/)() const | Kontrollerar om ett specifikt värde är null. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Kontrollerar om pekaren är i delat läge. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Kontrollerar om pekaren är i svagt läge. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Kontrollerar om pekaren inte är null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Kontrollerar om pekaren är null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Hämtar referens till det pekade objektet. Påstår att pekaren inte är null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Tillåter åtkomst till medlemmar i det refererade objektet. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Tillhandahåller mindre-jämförelse semantik för [SmartPtr](../../system/smartptr/)-klassen. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Tillhandahåller mindre-jämförelse semantik för [SmartPtr](../../system/smartptr/)-klassen. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Flyttar-assignerar [SmartPtr](../../system/smartptr/)-objektet. x blir oanvändbart. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopierar-assignerar [SmartPtr](../../system/smartptr/)-objektet. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopierar-assignerar [SmartPtr](../../system/smartptr/)-objektet. Utför nödvändiga typkonverteringar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Tilldelar råpekare till [SmartPtr](../../system/smartptr/)-objektet. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Sätter pekarvärdet till nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om pekaren pekar på nullptr. |
| **BitArray::Reference** [operator[]](./operator[]/)(int) const | Bitåtkomst. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Tar bort aliasing (skapad av en alias-konstruktor) från pekaren, säkerställer att den hanterar (om delad) eller spårar (om svag) samma objekt den pekar på. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Sätter det pekade objektet. |
| void [reset](../../system/smartptr/reset/)() | Gör så att pekaren pekar på nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Sätter pekarläget. Kan ändra referensräkningar för det refererade objektet. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Anropar SetTemplateWeakPtr()-metoden på det pekade objektet (om något). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Skapar nullpekare [SmartPtr](../../system/smartptr/)-objekt i önskat läge. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Skapar [SmartPtr](../../system/smartptr/) som pekar på specificerat objekt, eller konverterar råpekare till [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopieringskonstruktor för [SmartPtr](../../system/smartptr/)-objekt. Båda pekarna pekar på samma objekt efteråt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopieringskonstruktor för [SmartPtr](../../system/smartptr/)-objekt. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om tillåtet. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Flyttkonstruktor för [SmartPtr](../../system/smartptr/)-objekt. Byter i praktiken två pekare, om de båda har samma läge. x kan bli oanvändbart efter anropet. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konverterar typ av refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en arraytypcast som inte stöds i C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initierar en tom array. Används för att översätta vissa C#-konstrukt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruktor för en [SmartPtr](../../system/smartptr/) som delar ägandainformation med det ursprungliga värdet av ptr, men håller en orelaterad och ohanterad pekare p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Kastar pekaren till en annan typ med static_cast på det pekade objektet. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konverterar vilken pekartyp som helst till pekare till [Object](../../system/object/). Kräver inte att Pointee_-typen är komplett. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Kortkommando för att hämta [System::TypeInfo](../../system/typeinfo/)-objektet för Pointee_-typen. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Förstör [SmartPtr](../../system/smartptr/)-objektet. Om nödvändigt minskar den referensräknaren för det pekade objektet och raderar objektet. |
## Se även

* Klass [SmartPtr](../../system/smartptr/)
* Namnrymd [System::Collections](../)
* Bibliotek [Aspose.Slides](../../)