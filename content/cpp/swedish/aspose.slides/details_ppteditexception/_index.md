---
title: Details_PptEditException
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett undantag som kastas när ett fel vid redigering av presentation upptäcks.
type: docs
weight: 664
url: /sv/aspose.slides/details_ppteditexception/
---
## Details_PptEditException klass

Representerar ett undantag som kastas när ett fel vid redigering av presentation upptäcks.

```cpp
class Details_PptEditException : public Aspose::Slides::Details_PptException
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av referenstyp i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av värdetyp i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Returnerar en dictionary med anpassade undantagsdata. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Returnerar ett 32-bit heltalsvärde som är en HRESULT-kod kopplad till undantaget som representeras av det aktuella objektet. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Returnerar en referens till objektet som representerar det inre undantaget. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Returnerar strängen som innehåller felbeskrivningen. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Returnerar strängen som innehåller stackspåret. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Returnerar en kopia av Exception-objektet som representerar det innersta undantaget. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-statement. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med ett specificerat värde. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Ställer in HRESULT, ett kodad numeriskt värde som tilldelas ett specifikt undantag. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar det delade referensräknaren. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar det delade referensräknaren. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Returnerar strängrepresentationen av det aktuella objektet. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning för C# lock()-statement. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementerar [what()](../../system/details_exception/what/)-metoden som anropas av klassen [ExceptionWrapper](../../system/exceptionwrapper/). Trots att denna klass inte ärver från std::exception kan avledda klasser använda skyddade/privata medlemmar för att implementera deras logik. Att flytta denna metodimplementering till [ExceptionWrapper](../../system/exceptionwrapper/) kan bryta den logiken. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Details_PptException](../details_pptexception/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)