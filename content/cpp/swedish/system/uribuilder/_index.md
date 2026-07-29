---
title: UriBuilder
second_title: Aspose.Slides för C++ API-referens
description: "Tillhandahåller metoder för att konstruera och modifiera universella resursidentifierare (URI). Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Wrappa alltid denna klass i System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 1405
url: /sv/system/uribuilder/
---
## UriBuilder-klass

Tillhandahåller metoder för att konstruera och modifiera universella resursidentifierare (URIs). Objekt av den här klassen bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Wrappa alltid den här klassen i en [System::SmartPtr](../smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class UriBuilder : public System::Object
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Returnerar schemat för den URI som skapats av det aktuella objektet. |
| [SharedPtr](../sharedptr/)\<[Uri](../uri/)\> [get_Uri](./get_uri/)() const | Returnerar [Uri](../uri/)-objektet som konstruerats av det aktuella objektet. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../object/gettype/)-anropet. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar det delade referensräkningen med angivet värde. |
| void [set_Port](./set_port/)(int) | Anger portnumret för URI:n. |
| void [set_Scheme](./set_scheme/)(const [String](../string/)\&) | Ställer in schemat för den URI som skapats av det aktuella objektet till det angivna värdet. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en weak-pekare (istället för shared). Tillåter att byta pekare i containrar till weak-läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar nuvarande värde av den delade referensräknaren. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar den delade referensräkningen. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräkningen. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../string/) [ToString](./tostring/)() const override | Returnerar den strängrepresentation av den URI som skapats av det aktuella objektet. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktionen. |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
|  [UriBuilder](./uribuilder/)(const [String](../string/)\&) | Konstruerar ett [UriBuilder](./)-objekt som representerar den specificerade URI:n. |
|  [UriBuilder](./uribuilder/)(const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\&) | Konstruerar ett [UriBuilder](./)-objekt som representerar den specificerade URI:n. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar weak-referensräkningen. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar weak-referensräkningen. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |

## Se även

* Klass [Object](../object/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)