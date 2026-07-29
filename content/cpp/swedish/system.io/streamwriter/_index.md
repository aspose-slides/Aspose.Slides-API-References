---
title: StreamWriter
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en skrivare som skriver tecken till en byte-ström. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 391
url: /sv/system.io/streamwriter/
---
## StreamWriter klass

Representerar en skrivare som skriver tecken till en byte-ström. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrap alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Close](./close/)() override | Stänger strömmen och frigör förvärvade resurser. |
| void [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual void [Dispose](./dispose/)(**bool**) | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| void [Flush](./flush/)() override | Spolar innehållet i bufferten till den underliggande strömmen och spolar sedan den underliggande strömmen. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Returnerar ett värde som indikerar om [StreamWriter](./) kommer att spola data till den underliggande strömmen varje gång metoden [StreamWriter::Write](./write/) anropas. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Returnerar en delad pekare till ett objekt som representerar den underliggande strömmen. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Returnerar den för närvarande använda kodningen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Returnerar det för närvarande använda [IFormatProvider](../../system/iformatprovider/)-objektet. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Returnerar det för närvarande använda [IFormatProvider](../../system/iformatprovider/)-objektet. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Returnerar en radavslutningssträng. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Returnerar en radavslutningssträng. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning med C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Returnerar ett värde som specificerar om [StreamWriter](./) ska spola data till den underliggande strömmen varje gång metoden [StreamWriter::Write](./write/) anropas. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Ställer in en radavslutningssträng. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek 1024 byte. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna underliggande strömmen med den angivna kodningen och en buffert med standardstorlek 1024 byte. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna underliggande strömmen med den angivna kodningen och en buffert av angiven storlek. En parameter anger om den underliggande strömmen ska stängas när [StreamWriter](./)-objektet tas bort. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna filen med UTF-8-kodning och en buffert med standardstorlek 1024 byte. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna filen med den angivna kodningen och en buffert med standardstorlek 1024 byte. En parameter anger om data ska läggas till filen eller om filen ska skrivas över. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Skapar en instans av [StreamWriter](./)-objektet som skriver tecken till den angivna filen med den angivna kodningen och buffertstorlek. En parameter anger om data ska läggas till filen eller om filen ska skrivas över. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning med C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [Write](./write/)(char_t) override | Skriver det angivna tecknet till strömmen. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Skriver den angivna strängen till strömmen. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Skriver strängrepresentationen av det angivna objektet till strömmen. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Skriver alla tecken från den angivna arrayen till strömmen. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen till strömmen. |
| void [Write](./write/)(const char_t *) override | Skriver den angivna C-strängen till strömmen. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Skriver strängrepresentationen av det angivna objektet till strömmen. |
| virtual void [Write](../textwriter/write/)(**bool**) | Skriver strängrepresentationen av det angivna booleska värdet till strömmen. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Skriver strängrepresentationen av det angivna [Decimal](../../system/decimal/)-objektet till strömmen. |
| virtual void [Write](../textwriter/write/)(**double**) | Skriver strängrepresentationen av det angivna dubbelprecision flyttalvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(int) | Skriver strängrepresentationen av det angivna 32-bitars heltalsvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Skriver strängrepresentationen av det angivna 64-bitars heltalsvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(**float**) | Skriver strängrepresentationen av det angivna enkelprecision flyttalvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Skriver strängrepresentationen av det angivna osignerade 32-bitars heltalsvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Skriver strängrepresentationen av det angivna osignerade 64-bitars heltalsvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Skriver strängrepresentationen av det angivna [TypeInfo](../../system/typeinfo/)-objektet till strömmen. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet till strömmen. |
| void [WriteLine](./writeline/)() override | Skriver radavslutnings-tecken till strömmen. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Skriver den angivna strängen följt av radavslutnings-tecken till strömmen. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Skriver strängrepresentationen av det angivna objektet följt av radavslutnings-tecken till strömmen. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Skriver alla tecken från den angivna arrayen följt av radavslutnings-tecken till strömmen. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen följt av radavslutnings-tecken till strömmen. |
| void [WriteLine](./writeline/)(const char_t *) override | Skriver den angivna C-strängen följt av radavslutnings-tecken till strömmen. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Skriver strängrepresentationen av det angivna objektet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Skriver strängrepresentationen av det angivna booleska värdet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Skriver det angivna tecknet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Skriver strängrepresentationen av det angivna [Decimal](../../system/decimal/)-objektet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Skriver strängrepresentationen av det angivna dubbelprecision flyttalvärdet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Skriver strängrepresentationen av det angivna 32-bitars heltalsvärdet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Skriver strängrepresentationen av det angivna 64-bitars heltalsvärdet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Skriver strängrepresentationen av det angivna enkelprecision flyttalvärdet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Skriver strängrepresentationen av det angivna osignerade 32-bitars heltalsvärdet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Skriver strängrepresentationen av det angivna osignerade 64-bitars heltalsvärdet följt av radavslutnings-tecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Skriver strängrepresentationen av det angivna [TypeInfo](../../system/typeinfo/)-objektet följt av radavslutnings-tecken till strömmen. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet följt av radavslutnings-tecken till strömmen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
| [~StreamWriter](./~streamwriter/)() | Destruktor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Se även

* Klass [TextWriter](../textwriter/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)