---
title: SmartPtr
second_title: Aspose.Slides för C++ API-referens
description: "Pekarklass för att omsluta typer som allokeras på heapen. Använd den för att hantera minne för klasser som ärver Object. Denna pekartyp följer intrusiv pekarsemantik. Referensräknaren lagras antingen i Object själv eller i en räknarstruktur som är tätt kopplad till Object-instansen. I alla fall bildar alla SmartPtr-instanser en enda ägandegrupp oavsett hur de skapades, vilket skiljer sig från hur std::shared_ptr-klassen beter sig. Att konvertera en råpekare till SmartPtr är säkert så länge det finns andra SmartPtr-instanser som har delade referenser till samma objekt. SmartPtr-klassinstans kan vara i ett av två tillstånd: delad pekare och svag pekare. För att hålla objektet levande bör antalet delade referenser till det vara positivt. Både svaga och delade pekare kan användas för att komma åt det pekade objektet (för att anropa metoder, läsa eller skriva fält osv.), men svaga pekare deltar inte i referensräkningen för delade pekare. Object tas bort när den sista 'shared' SmartPtr-pekaren till den förstörs. Se därför till att detta inte händer när inga andra delade SmartPtr-pekare till objektet finns, t.ex. under objektkonstruktion eller -destruktion. Använd System::Object::ThisProtector-säkerhetsobjekt (i C++-kod) eller CppCTORSelfReference- eller CppSelfReference-attribut (i C#-kod som översätts) för att lösa detta problem. På liknande sätt, se till att bryta referensloopar genom att använda System::WeakPtr-pekarklass eller System::SmartPtrMode::Weak-pekarläge (i C++-kod) eller CppWeakPtr-attribut (i C#-kod som översätts). Om två eller fler objekt refererar till varandra med 'shared'-pekare, kommer de aldrig att tas bort. Om pekartypen (svag eller delad) ska ändras vid körning, använd System::SmartPtr<T>::set_Mode()-metoden eller System::DynamicWeakPtr-klassen. SmartPtr-klassen innehåller inga virtuella metoder. Du bör endast ärva den om du skapar en egen minneshanteringsstrategi. Denna typ är en pekare för att hantera ett annat objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens."
type: docs
weight: 1236
url: /sv/system/smartptr/
---
## SmartPtr klass

Pekarklass för att omsluta typer som allokeras på heapen. Använd den för att hantera minne för klasser som ärver [Object](../object/). Denna pekartyp följer intrusiva pekarsemantik. Referensräknaren lagras antingen i [Object](../object/) själv eller i en räknarstruktur som är tätt knuten till [Object](../object/)-instansen. I vilket fall som helst bildar alla [SmartPtr](./)-instanser en enda ägandegrupp oavsett hur de skapades, vilket skiljer sig från hur std::shared_ptr-klass beter sig. Att konvertera råpekare till [SmartPtr](./) är säkert så länge det finns andra [SmartPtr](./)-instanser som har delade referenser till samma objekt. [SmartPtr](./)-klassinstans kan vara i ett av två tillstånd: delad pekare och svag pekare. För att hålla objektet levande bör antalet delade referenser till det vara positivt. Både svaga och delade pekare kan användas för att komma åt det pekade objektet (för att anropa metoder, läsa eller skriva fält osv.), men svaga pekare deltar inte i referensräkningen för delade pekare. [Object](../object/) tas bort när den sista 'delade' [SmartPtr](./)-pekaren till den förstörs. Se därför till att detta inte sker när inga andra delade [SmartPtr](./)-pekare till objektet finns, t.ex. under objektkonstruktion eller -destruktion. Använd System::Object::ThisProtector-säkerhetsobjekt (i C++-kod) eller CppCTORSelfReference- eller CppSelfReference-attribut (i C#-kod som översätts) för att åtgärda detta problem. På liknande sätt, se till att bryta loopreferenser genom att använda [System::WeakPtr](../weakptr/)-pekarklass eller [System::SmartPtrMode::Weak](../smartptrmode/)-pekmode (i C++-kod) eller CppWeakPtr-attribut (i C#-kod som översätts). Om två eller fler objekt refererar till varandra med 'delade' pekare, kommer de aldrig att tas bort. Om pekartypen (svag eller delad) bör bytas under körning, använd [System::SmartPtr<T>::set_Mode()](./set_mode/)-metoden eller [System::DynamicWeakPtr](../dynamicweakptr/)-klassen. [SmartPtr](./)-klass innehåller inga virtuella metoder. Du bör bara ärva den om du skapar en egen minneshanteringsstrategi. Denna typ är en pekare för att hantera ett annat objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens.

```cpp
template<class T>class SmartPtr
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på det pekade objektet. Måste vara antingen [System::Object](../object/) eller en underklass till den. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| auto [begin](./begin/)() | Åtkomstfunktion för [begin()](./begin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [begin()](./begin/)-metoden. |
| auto [begin](./begin/)() const | Åtkomstfunktion för [begin()](./begin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [begin()](./begin/)-metoden. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Kastar pekaren till dess egen typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Kastar pekaren till basklassen med static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Kastar pekaren till en avledd typ med dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Kastar pekaren till en avledd typ med dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Åtkomstfunktion för [cbegin()](./cbegin/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [cbegin()](./cbegin/)-metoden. |
| auto [cend](./cend/)() const | Åtkomstfunktion för [cend()](./cend/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [cend()](./cend/)-metoden. |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Kastar pekaren till en annan typ med const_cast på det pekade objektet. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Kastar pekaren till en annan typ med dynamic_cast på det pekade objektet. |
| auto [end](./end/)() | Åtkomstfunktion för [end()](./end/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [end()](./end/)-metoden. |
| auto [end](./end/)() const | Åtkomstfunktion för [end()](./end/)-metoden i en underliggande samling. Kompilerar endast om SmartPtr_ är en specialiseringstyp med [end()](./end/)-metoden. |
| [Pointee_](./pointee_/) * [get](./get/)() const | Hämtar det pekade objektet. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Hämtar pekarläget. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Hämtar det pekade objektet, men påstår att pekaren är i delat läge. |
| int [get_shared_count](./get_shared_count/)() const | Hämtar antalet delade pekare som finns till det refererade objektet, inklusive den nuvarande. Påstår att den nuvarande pekaren är i delat läge. |
| int [GetHashCode](./gethashcode/)() const | Anropar [GetHashCode()](./gethashcode/) på det pekade objektet. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Hämtar det för närvarande refererade objektet (om något) eller kastar ett undantag. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Hämtar det pekade objektet (om något) eller nullptr. Samma som [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Hämtar det refererade objektet. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Hämtar det pekade objektet (om något) eller nullptr. Samma som [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Kontrollerar om det pekade objektet är av en viss typ eller en undertyp. Följer C#-'is'-semantik. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Kontrollerar om pekaren pekar på ett annat objekt än det som ägs (skapat av en aliaskonstruktör). |
| **bool** [IsShared](./isshared/)() const | Kontrollerar om pekaren är i delat läge. |
| **bool** [IsWeak](./isweak/)() const | Kontrollerar om pekaren är i svagt läge. |
| explicit  [operator bool](./operator_bool/)() const | Kontrollerar om pekaren inte är null. |
| **bool** [operator!](./operator_not/)() const | Kontrollerar om pekaren är null. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Hämtar referens till det pekade objektet. Påstår att pekaren inte är null. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Möjliggör åtkomst till medlemmar i det refererade objektet. |
| **bool** [operator<](./operator_less/)(Y *) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](./)-klassen. |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Tillhandahåller mindre-jämförelse-semantik för [SmartPtr](./)-klassen. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Flytt-tilldelar [SmartPtr](./)-objektet. x blir oanvändbart. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Kopierar-tilldelar [SmartPtr](./)-objektet. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Kopierar-tilldelar [SmartPtr](./)-objektet. Utför nödvändiga typkonverteringar. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Tilldelar råpekare till [SmartPtr](./)-objektet. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Sätter pekarvärdet till nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om pekaren pekar på nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Tar bort aliasing (skapat av en aliaskonstruktör) från pekaren, säkerställer att den hanterar (om delad) eller spårar (om svag) samma objekt som den pekar på. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Sätter det pekade objektet. |
| void [reset](./reset/)() | Gör så att pekaren pekar på nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Sätter pekarläget. Kan ändra referensräkningen för det refererade objektet. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Anropar SetTemplateWeakPtr()-metoden på det pekade objektet (om något). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Skapar [SmartPtr](./)-objekt av önskat läge. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Skapar null-pekare [SmartPtr](./)-objekt av önskat läge. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Skapar [SmartPtr](./) som pekar på specificerat objekt, eller konverterar råpekare till [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopierar-konstruktör för [SmartPtr](./)-objekt. Båda pekarna pekar på samma objekt efteråt. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopierar-konstruktör för [SmartPtr](./)-objekt. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om tillåtet. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Flytt-konstruktör för [SmartPtr](./)-objekt. Byter i praktiken två pekare om de har samma läge. x kan bli oanvändbart efter anropet. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Konverterar typen på den refererade arrayen genom att skapa en ny array av annan typ. Användbart om det i C# finns en array-typcast som inte stöds i C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Initierar en tom array. Används för att översätta vissa C#-kodkonstruktioner. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruerar en [SmartPtr](./) som delar ägandinformation med det ursprungliga värdet av ptr, men håller en orelaterad och ohanterad pekare p. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Kastar pekaren till en annan typ med static_cast på det pekade objektet. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Konverterar vilken pekartyp som helst till pekare till [Object](../object/). Kräver inte att Pointee_-typen är komplett. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Genväg för att få [System::TypeInfo](../typeinfo/)-objektet för Pointee_-typen. |
|  [~SmartPtr](./~smartptr/)() | Förstör [SmartPtr](./)-objektet. Vid behov minskar den referensräkningen för det pekade objektet och tar bort objektet. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Pointee_](./pointee_/) | Pekad typ. |
| [SmartPtr_](./smartptr_/) | Specialiserad smartpekartyp. |
| [ArrayType](./arraytype/) | Samma som Pointee_, om det är en specialisering av [System::Array](../array/), annars void. |
| [ValueType](./valuetype/) | Lagringstyp för pekad array. Endast meningsfull om T är en specialisering av [System::Array](../array/). |

## Se även

* Namespace [System](../)
* Library [Aspose.Slides](../../)