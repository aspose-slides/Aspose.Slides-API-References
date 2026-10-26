---
title: TextWriter
second_title: Aspose.Slides för C++ API-referens
description: "En basklass för klasser som representerar skribenter som skriver sekvenser av tecken till olika destinationer. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningstidfel och/eller assertionsfel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 443
url: /sv/system.io/textwriter/
---
## TextWriter klass

En basisklass för klasser som representerar skribenter som skriver teckensekvenser till olika destinationer. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningstidfel och/eller assertionsfel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class TextWriter : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Close](./close/)() | Stänger strömmen och frigör förvärvade resurser. |
| void [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual void [Flush](./flush/)() | Spolar bufferinnehållet till den underliggande strömmen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Returnerar den för närvarande använda kodningen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Returnerar det för närvarande använda [IFormatProvider](../../system/iformatprovider/)-objektet. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Returnerar det för närvarande använda [IFormatProvider](../../system/iformatprovider/)-objektet. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Returnerar en radavslutningssträng. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Returnerar en radavslutningssträng. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiskt typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivas av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Ställer in en radavslutningssträng. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (i stället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Skriver strängrepresentationen av det angivna objektet till strömmen. |
| virtual void [Write](./write/)(**bool**) | Skriver strängrepresentationen av det angivna boolska värdet till strömmen. |
| virtual void [Write](./write/)(char_t) | Skriver det angivna tecknet till strömmen. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Skriver strängrepresentationen av det angivna [Decimal](../../system/decimal/)-objektet till strömmen. |
| virtual void [Write](./write/)(**double**) | Skriver strängrepresentationen av det angivna dubbelprecisions-flyttalvärdet till strömmen. |
| virtual void [Write](./write/)(int) | Skriver strängrepresentationen av det angivna 32-bit-heltalvärdet till strömmen. |
| virtual void [Write](./write/)(**int64_t**) | Skriver strängrepresentationen av det angivna 64-bit-heltalvärdet till strömmen. |
| virtual void [Write](./write/)(**float**) | Skriver strängrepresentationen av det angivna enkelprecisions-flyttalvärdet till strömmen. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Skriver den angivna strängen till strömmen. |
| virtual void [Write](./write/)(**uint32_t**) | Skriver strängrepresentationen av det angivna icke-signerade 32-bit-heltalvärdet till strömmen. |
| virtual void [Write](./write/)(**uint64_t**) | Skriver strängrepresentationen av det angivna icke-signerade 64-bit-heltalvärdet till strömmen. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Skriver alla tecken från den angivna arrayen till strömmen. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen till strömmen. |
| virtual void [Write](./write/)(const char_t *) | Skriver den angivna C-strängen till strömmen. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Skriver strängrepresentationen av det angivna [TypeInfo](../../system/typeinfo/)-objektet till strömmen. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet till strömmen. |
| virtual void [WriteLine](./writeline/)() | Skriver radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Skriver strängrepresentationen av det angivna objektet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(**bool**) | Skriver strängrepresentationen av det angivna boolska värdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(char_t) | Skriver det angivna tecknet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Skriver strängrepresentationen av det angivna [Decimal](../../system/decimal/)-objektet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(**double**) | Skriver strängrepresentationen av det angivna dubbelprecisions-flyttalvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(int) | Skriver strängrepresentationen av det angivna 32-bit-heltalvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Skriver strängrepresentationen av det angivna 64-bit-heltalvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(**float**) | Skriver strängrepresentationen av det angivna enkelprecisions-flyttalvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Skriver den angivna strängen följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Skriver strängrepresentationen av det angivna icke-signerade 32-bit-heltalvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Skriver strängrepresentationen av det angivna icke-signerade 64-bit-heltalvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Skriver alla tecken från den angivna arrayen följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Skriver den angivna C-strängen följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Skriver strängrepresentationen av det angivna [TypeInfo](../../system/typeinfo/)-objektet följt av radavslutningstecken till strömmen. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet följt av radavslutningstecken till strömmen. |
| virtual  [~Object](../../system/object/~object/)() | Destroyar objektet. Frigir alla interna datastrukturer. |
| virtual  [~TextWriter](./~textwriter/)() | Destruktor. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till den här klassen. |

## Se även

* Klass [IDisposable](../../system/idisposable/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)