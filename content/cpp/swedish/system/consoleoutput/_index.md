---
title: ConsoleOutput
second_title: Aspose.Slides för C++ API-referens
description: "Representerar standardutgångsströmmen. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 209
url: /sv/system/consoleoutput/
---
## ConsoleOutput-klass

Representerar standardutgångsströmmen. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Stänger strömmen och frigör förvärvade resurser. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalss jämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalss jämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Spolar innehållet i bufferten till den underliggande strömmen. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Returnerar alltid ASCII-kodning. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Returnerar det aktuellt använda [IFormatProvider](../iformatprovider/)-objektet. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Returnerar det aktuellt använda [IFormatProvider](../iformatprovider/)-objektet. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Returnerar en radavslutningssträng. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Returnerar en radavslutningssträng. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknar-datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../object/gettype/)-anropet. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objektet. Initialiserar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Ställer in en radavslutningssträng. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog till C# [Object.ToString()](../object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktion. |
| void [Unlock](../object/unlock/)() | Implementerar upplåsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [Write](./write/)(**bool**) override | Skriver ut strängrepresentationen av det angivna bool-värdet till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Skriver ut strängrepresentationen av det angivna objektet till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(char_t) override | Skriver ut det angivna teckenvärdet till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)([Decimal](../decimal/)) override | Skriver ut strängrepresentationen av [Decimal](../decimal/)-värdet till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(**double**) override | Skriver ut strängrepresentationen av dubbelprecisionens flyttal till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(**int32_t**) override | Skriver ut strängrepresentationen av 32-bitars heltalsvärde till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(**int64_t**) override | Skriver ut strängrepresentationen av 64-bitars heltalsvärde till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(**float**) override | Skriver ut strängrepresentationen av enkelprecisionens flyttal till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(const [String](../string/)\&) override | Skriver ut det angivna strängobjektet till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(**uint32_t**) override | Skriver ut strängrepresentationen av icke-signerat 32-bitars heltalsvärde till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(**uint64_t**) override | Skriver ut strängrepresentationen av icke-signerat 64-bitars heltalsvärde till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Skriver ut strängrepresentationen av den angivna teckenarrayen till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Skriver ut strängrepresentationen av ett intervall av värden i den angivna teckenarrayen till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(const char_t *) override | Skriver ut den angivna c-strängen till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Skriver ut strängrepresentationen av det angivna [TypeInfo](../typeinfo/)-objektet till utdataströmmen som representeras av det aktuella objektet. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Skriver strängrepresentationen av det angivna 32-bitars heltalsvärdet till strömmen. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet till strömmen. |
| void [WriteLine](./writeline/)() override | Skriver ut den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Skriver ut strängrepresentationen av det angivna objektet följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(**bool**) override | Skriver ut strängrepresentationen av det angivna bool-värdet följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(char_t) override | Skriver ut det angivna teckenvärdet följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Skriver ut strängrepresentationen av [Decimal](../decimal/)-värdet följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(**double**) override | Skriver ut strängrepresentationen av dubbelprecisionens flyttal följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(int) override | Skriver ut strängrepresentationen av 32-bitars heltalsvärde följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(**int64_t**) override | Skriver ut strängrepresentationen av 64-bitars heltalsvärde följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(**float**) override | Skriver ut strängrepresentationen av enkelprecisionens flyttal följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Skriver ut det angivna strängobjektet följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Skriver ut strängrepresentationen av icke-signerat 32-bitars heltalsvärde följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Skriver ut strängrepresentationen av icke-signerat 64-bitars heltalsvärde följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Skriver ut strängrepresentationen av den angivna teckenarrayen följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Skriver ut strängrepresentationen av ett intervall av värden i den angivna teckenarrayen följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(const char_t *) override | Skriver ut den angivna c-strängen följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Skriver ut strängrepresentationen av det angivna [TypeInfo](../typeinfo/)-objektet följt av den aktuella radavslutningssträngen till utdataströmmen som representeras av det aktuella objektet. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet följt av radavslutningstecken till strömmen. |
| virtual  [~Object](../object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destruktor. |

## Se även

* Klass [TextWriter](../../system.io/textwriter/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)