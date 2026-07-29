---
title: SHA1
second_title: Aspose.Slides för C++ API-referens
description: "Beräknar SHA1-hash för indata. I C++ är SHA1 inte en abstrakt klass. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 534
url: /sv/system.security.cryptography/sha1/
---
## SHA1 klass


Beräknar [SHA1](./) hash för indata. I C++ är [SHA1](./) inte en abstrakt klass. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SHA1 : public System::Security::Cryptography::HashAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](../hashalgorithm/computehash/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Hashar bufferten. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](../hashalgorithm/computehash/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Hashar en buffertdel. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](../hashalgorithm/computehash/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> const\&) | Läser ström tills slutet och beräknar hash för de lästa data. |
| static [SharedPtr](../../system/sharedptr/)\<[SHA1](./)\> [Create](./create/)() | Skapar en instans av hash-algoritmen. |
| static [SharedPtr](../../system/sharedptr/)\<[SHA1](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Skapar en instans av hash-algoritmen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Hash](../hashalgorithm/get_hash/)() | Hämtar värdet av den beräknade hash-koden. |
| virtual int [get_HashSize](../hashalgorithm/get_hashsize/)() | Hämtar storleken på den beräknade hash-värdet i byte. |
| int [get_InputBlockSize](../hashalgorithm/get_inputblocksize/)() override | Indata-blockstorlek. |
| int [get_OutputBlockSize](../hashalgorithm/get_outputblocksize/)() override | Utdata-blockstorlek. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual void [Initialize](../hashalgorithm/initialize/)() | Återställer hash-generatorn till initialt tillstånd. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsen för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar det aktuella värdet för den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| int [TransformBlock](../hashalgorithm/transformblock/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Bearbetar ett datablock och kopierar data till utmatningsarrayen. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [TransformFinalBlock](../hashalgorithm/transformfinalblock/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Bearbetar sista datablocket och beräknar hash. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsen för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräknaren. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementerar den svaga referensräknaren. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~HashAlgorithm](../hashalgorithm/~hashalgorithm/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [HashAlgorithm](../hashalgorithm/)
* Namnrymd [System::Security::Cryptography](../)
* Bibliotek [Aspose.Slides](../../)