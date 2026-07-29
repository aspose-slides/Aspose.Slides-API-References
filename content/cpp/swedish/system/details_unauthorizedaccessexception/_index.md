---
title: Details_UnauthorizedAccessException
second_title: Aspose.Slides för C++ API-referens
description: "UnauthorizedAccessException kastas när åtkomst nekas av operativsystemet på grund av ett I/O-fel eller ett säkerhetsfel. Skapa aldrig instanser av denna klass manuellt. Använd UnauthorizedAccessException-klassen istället. Bädda aldrig in UnauthorizedAccessException-klassens instanser i System::SmartPtr."
type: docs
weight: 755
url: /sv/system/details_unauthorizedaccessexception/
---
## Details_UnauthorizedAccessException klass


UnauthorizedAccessException kastas när åtkomst nekas av operativsystemet på grund av ett I/O-fel eller ett säkerhetsfel. Skapa aldrig instanser av denna klass manuellt. Använd UnauthorizedAccessException-klass istället. Bädda aldrig in UnauthorizedAccessException-klassens instanser i [System::SmartPtr](../smartptr/).

```cpp
class Details_UnauthorizedAccessException : public System::Details_SystemException
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Returnerar en ordbok med anpassad undantagsdata. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Returnerar ett 32-bitars heltalsvärde som är en HRESULT-kod kopplad till undantaget som representeras av det aktuella objektet. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Returnerar en referens till objektet som representerar det inre undantaget. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Returnerar strängen som innehåller felbeskrivningen. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Returnerar strängen som innehåller stackspåret. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Returnerar en kopia av Exception-objektet som representerar det innersta undantaget. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur kopplad till objektet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../object/gettype/)-anrop. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementerar C# lock()-uttalandet för låsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Sätter HRESULT, ett kodade numeriska värde som tilldelas ett specifikt undantag. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde på delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Returnerar strängrepresentationen av det aktuella objektet. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-uttalandet för upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementerar [what()](../details_exception/what/)-metoden som anropas av [ExceptionWrapper](../exceptionwrapper/)-klassen. Trots att denna klass inte ärver från std::exception kan härledda klasser använda skyddade/privata medlemmar för att implementera sin logik. Att flytta denna metodimplementation till [ExceptionWrapper](../exceptionwrapper/) kan bryta den logiken. |
| virtual  [~Object](../object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Details_SystemException](../details_systemexception/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)