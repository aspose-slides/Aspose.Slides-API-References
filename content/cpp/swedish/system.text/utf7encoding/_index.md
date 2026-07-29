---
title: UTF7Encoding
second_title: Aspose.Slides för C++ API-referens
description: "UTF-7-kodning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 365
url: /sv/system.text/utf7encoding/
---
## UTF7Encoding klass


UTF-7-kodning. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klonar kodningsobjektet. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Konverterar byte mellan två kodningar. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Konverterar byte mellan två kodningar. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Jämför med objektet. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil jämförelse av dubbelprecisionsflyttal där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Hämtar ASCII-kodning. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Hämtar standard-big-endian Unicode-kodningsobjekt. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Hämtar standard-big-endian UTF-32-kodningsobjekt. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Hämtar namn på kodning som är kompatibel med e-postagentens brödtext. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Hämtar [Windows](../../system.windows/) kodsidens ID. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Hämtar avkodarens fallback. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Hämtar standardkodning. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Hämtar kodarens fallback. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Hämtar människoläsbart namn på kodning. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Hämtar namn på kodning som är kompatibel med e-postagentens header. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Kontrollerar om kodning kan användas i webbläsare för att visa innehåll. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Kontrollerar om kodning kan användas i webbläsare för att spara innehåll. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Kontrollerar om kodning kan användas i e-postklient för att visa innehåll. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Kontrollerar om kodning kan användas i e-postklient för att spara innehåll. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Kontrollerar om kodning är skrivskyddad. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Kontrollerar om kodning är enstaka byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Hämtar Latin1-kodning. FÖR INTERN ANVÄNDNING. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Hämtar standard-Unicode-kodningsobjekt. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Hämtar standard-UTF-7-kodningsobjekt. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Hämtar standard-UTF-8-kodningsobjekt. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Endast intern, avsedd för användning av klassbiblioteken: Omärkt och utan indata-validering. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Hämtar IANA-kompatibelt kodningsnamn. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Hämtar [Windows](../../system.windows/) kodsidens ID. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | Hämtar antalet tecken som behövs för att koda en teckenbuffert. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Hämtar antalet tecken som behövs för att koda en teckenbuffert. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Hämtar antalet tecken som behövs för att koda en teckenbuffert. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Hämtar antalet tecken som behövs för att koda en teckenbuffert. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Hämtar antalet tecken som behövs för att koda en teckenbuffert. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Hämtar antalet tecken som behövs för att koda en teckenbuffert. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Hämtar antalet tecken som behövs för att koda en teckenbuffert. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Hämtar byte som resultat av kodning av en teckenbuffert. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | Hämtar byte som resultat av kodning av en teckenbuffert. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Hämtar byte som resultat av kodning av en teckenbuffert. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Hämtar byte som resultat av kodning av en teckenbuffert. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Hämtar antalet tecken som behövs för att avkoda en byte-buffert. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | Hämtar antalet tecken som behövs för att avkoda en byte-buffert. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Hämtar antalet tecken som behövs för att avkoda en byte-buffert. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Hämtar antalet tecken som behövs för att avkoda en byte-buffert. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Hämtar antalet tecken som behövs för att avkoda en byte-buffert. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | Hämtar tecknen som resultat av avkodning av en byte-buffert. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | Hämtar tecknen som resultat av avkodning av en byte-buffert. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Hämtar tecknen som resultat av avkodning av en byte-buffert. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Hämtar tecknen som resultat av avkodning av en byte-buffert. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Hämtar tecknen som resultat av avkodning av en byte-buffert. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Hämtar tecknen som resultat av avkodning av en byte-buffert. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | Hämtar en avkodare som vidarebefordrar förfrågningar till detta objekt. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | Hämtar en kodare som vidarebefordrar förfrågningar till detta objekt. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Hämtar kodning efter namn. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Hämtar kodning efter kodsida. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Hämtar kodning efter kodsida. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Hämtar kodning efter namn. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Hämtar lista över kända kodningar. |
| int [GetHashCode](./gethashcode/)() const override | Hämtar kodningens hash-kod. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Hämtar maximalt antal byte som behövs för att koda ett angivet antal tecken. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Hämtar maximalt antal tecken som behövs för att avkoda ett angivet antal byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | Returnerar en sekvens av byte som anger kodningen (t.ex. BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Avkodar en byte-buffert till en sträng. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Avkodar en byte-buffert till en sträng. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Avkodar en byte-buffert till en sträng. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Avkodar en byte-buffert till en sträng. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Avkodar en byte-buffert till en sträng. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Avkodar en byte-buffert till en sträng. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Avkodar en byte-buffert till en sträng. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Avkodar en byte-buffert till en sträng. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Avkodar en byte-buffert till en sträng. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som targetType beskriver. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Gör det möjligt att klona anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | Jämför kodningsparametrar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens för värdestypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delat referensräknare med angivet värde. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ställer in avkodarens fallback. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Ställer in kodarens fallback. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde på delat referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delat referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delat referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning för C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
|  [UTF7Encoding](./utf7encoding/)() | Konstruktor. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | Konstruktor. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardvärde för kodsida. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Magiskt tal som används av [Windows](../../system.windows/) för UTF-7 kodsidens ID. |

## Se också

* Klass [Encoding](../encoding/)
* Namnrymd [System::Text](../)
* Bibliotek [Aspose.Slides](../../)