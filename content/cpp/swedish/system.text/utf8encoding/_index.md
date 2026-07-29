---
title: UTF8Encoding
second_title: Aspose.Slides för C++ API-referens
description: "UTF-8-kodning. Objekt av den här klassen bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 378
url: /sv/system.text/utf8encoding/
---
## UTF8Encoding klass


UTF-8 kodning. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class UTF8Encoding : public System::Text::ICUEncoding
```

## Metoder

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klonar kodningsobjekt. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Konverterar byte mellan två kodningar. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Konverterar byte mellan två kodningar. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Jämför med objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Hämtar ASCII-kodning. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Hämtar det standardbig-endian Unicode-kodningsobjektet. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Hämtar det standardbig-endian UTF-32-kodningsobjektet. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Hämtar kodningsnamn som är kompatibelt med e-postagents brödtext. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Hämtar [Windows](../../system.windows/) kodsid-ID. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Hämtar avkodarfallback. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Hämtar standardkodning. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Hämtar kodarfallback. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Hämtar människoläsbart kodningsnamn. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Hämtar kodningsnamn kompatibelt med e-postagents rubrik. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Kontrollerar om kodning kan användas i en webbläsare för att visa innehåll. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Kontrollerar om kodning kan användas i en webbläsare för att spara innehåll. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Kontrollerar om kodning kan användas i e-postklient för att visa innehåll. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Kontrollerar om kodning kan användas i e-postklient för att spara innehåll. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Kontrollerar om kodning är skrivskyddad. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Kontrollerar om kodning är enstaka byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Hämtar Latin1-kodning. FÖR INTERN ANVÄNDNING. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Hämtar det standard Unicode-kodningsobjektet. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Hämtar det standard UTF-7-kodningsobjektet. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Hämtar det standard UTF-8-kodningsobjektet. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Endast internt, avsedd för klassbibliotek: Omarkerad och utan inmatningsvalidering. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Hämtar ett IANA-kompatibelt kodningsnamn. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Hämtar [Windows](../../system.windows/) kodsid-ID. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Hämtar antalet tecken som behövs för att koda en teckenbuffer. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Hämtar de byte som resultat av att koda en teckenbuffer. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Hämtar de byte som resultat av att koda en teckenbuffer. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Hämtar antalet tecken som behövs för att avkoda en bytebuffer. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Hämtar antalet tecken som behövs för att avkoda en bytebuffer. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Hämtar antalet tecken som behövs för att avkoda en bytebuffer. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Hämtar antalet tecken som behövs för att avkoda en bytebuffer. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Hämtar de tecken som resultat av att avkoda en bytebuffer. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Hämtar de tecken som resultat av att avkoda en bytebuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Hämtar de tecken som resultat av att avkoda en bytebuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Hämtar de tecken som resultat av att avkoda en bytebuffer. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Hämtar de tecken som resultat av att avkoda en bytebuffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenskontostrukturen som är associerad med objektet. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Hämtar en avkodare som vidarebefordrar förfrågningar till detta objekt. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Hämtar en kodare som vidarebefordrar förfrågningar till detta objekt. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Hämtar kodning efter namn. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Hämtar kodning efter kodsid. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Hämtar kodning efter kodsid. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Hämtar kodning efter namn. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Hämtar lista över kända kodningar. |
| int [GetHashCode](./gethashcode/)() const override | Hämtar kodningens hash-kod. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Hämtar maximalt antal byte som behövs för att koda ett angivet antal tecken. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Hämtar maximalt antal tecken som behövs för att avkoda ett angivet antal byte. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | Hämtar kodsidspreambel. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Avkodar en bytebuffer till en sträng. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Avkodar en bytebuffer till en sträng. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Avkodar en bytebuffer till en sträng. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Avkodar en bytebuffer till en sträng. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Avkodar en bytebuffer till en sträng. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Avkodar en bytebuffer till en sträng. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Avkodar en bytebuffer till en sträng. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Avkodar en bytebuffer till en sträng. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiskt typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF8Encoding](./)\&) const | Jämför kodningsparametrar. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Jämför kodningar med kodsidor. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delat referensräknare med angivet värde. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ställer in avkodarfallback. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Ställer in kodarfallback. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
|  [UTF8Encoding](./utf8encoding/)() | Konstruktor. |
|  [UTF8Encoding](./utf8encoding/)(**bool**) | Konstruktor. |
|  [UTF8Encoding](./utf8encoding/)(**bool**, **bool**) | Konstruktor. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Fält

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardkodsid-värde. |
| static constexpr [UTF8_CODE_PAGE](./utf8_code_page/) | RTTI-information. |

## Se också

* Klass [ICUEncoding](../icuencoding/)
* Namnutrymme [System::Text](../)
* Bibliotek [Aspose.Slides](../../)