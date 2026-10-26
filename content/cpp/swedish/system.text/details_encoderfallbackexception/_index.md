---
title: Details_EncoderFallbackException
second_title: Aspose.Slides för C++ API-referens
description: "Undantag kastas av EncoderExceptionFallback när kodning misslyckas. Skapa aldrig instanser av den här klassen manuellt. Använd EncoderFallbackException-klassen istället. Kapsla aldrig in EncoderFallbackException-klassens instanser i System::SmartPtr."
type: docs
weight: 118
url: /sv/system.text/details_encoderfallbackexception/
---
## Details_EncoderFallbackException klass

Undantag kastas av [EncoderExceptionFallback](../encoderexceptionfallback/) när kodning misslyckas. Skapa aldrig instanser av den här klass manuellt. Använd EncoderFallbackException klass istället. Kapsla aldrig in EncoderFallbackException klass instanser i [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_EncoderFallbackException : public System::Details_ArgumentException
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| char_t [get_CharUnknown](./get_charunknown/)() | Hämtar tecken som utlöstes fel. |
| char_t [get_CharUnknownHigh](./get_charunknownhigh/)() | Hämtar det höga tecknet i paret som utlöstes fel. |
| char_t [get_CharUnknownLow](./get_charunknownlow/)() | Hämtar det låga tecknet i paret som utlöstes fel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Returnerar en ordbok med anpassad undantagsdata. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Returnerar ett 32-bit heltal som är en HRESULT-kod kopplad till undantaget som representeras av det aktuella objektet. |
| int [get_Index](./get_index/)() | Hämtar positionen för tecknet som utlöstes fel i indatamatrisen. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Returnerar en referens till objektet som representerar det inre undantaget. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Returnerar strängen som innehåller felbeskrivningen. |
| [String](../../system/string/) [get_ParamName](../../system/details_argumentexception/get_paramname/)() |  |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Returnerar strängen som innehåller stackspåret. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Returnerar en kopia av Exception-objektet som representerar det innersta undantaget. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_argumentexception/gettype/)() const override | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| **bool** [Is](../../system/details_argumentexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Ställer in HRESULT, ett kodade numeriska värde som tilldelas ett specifikt undantag. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Returnerar strängrepresentationen av det aktuella objektet. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_argumentexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementerar [what()](../../system/details_exception/what/)-metoden som anropas av [ExceptionWrapper](../../system/exceptionwrapper/) klass. Trots att denna klass inte ärvs från std::exception-baserade klasser kan avledda klasser använda skyddade/privata medlemmar för att implementera sin logik. Att flytta denna metodimplementation till [ExceptionWrapper](../../system/exceptionwrapper/) kan bryta den logiken. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Details_ArgumentException](../../system/details_argumentexception/)
* Namnrymd [System::Text](../)
* Bibliotek [Aspose.Slides](../../)