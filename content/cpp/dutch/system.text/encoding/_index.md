---
title: Encoding
second_title: Aspose.Slides voor C++ API-referentie
description: Coderingsservices.
type: docs
weight: 222
url: /nl/system.text/encoding/
---
## Encoding klasse

[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Dupliceert coderingsobject. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Converteert bytes tussen twee coderingen. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Converteert bytes tussen twee coderingen. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt coderingen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige zwevende-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige zwevende-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Verkrijgt ASCII-codering. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Verkrijgt het standaard big-endian Unicode-coderingsobject. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Verkrijgt het standaard big-endian UTF-32-coderingsobject. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Haalt de met mailagent-body compatibele coderingsnaam op. |
| virtual int [get_CodePage](./get_codepage/)() | Haalt [Windows](../../system.windows/) codepagina-ID op. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Haalt decoderfallback op. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Haalt standaardcodering op. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Haalt encoderfallback op. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Haalt menselijk leesbare coderingsnaam op. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Haalt de door mailagent-header compatibele coderingsnaam op. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Controleert of codering kan worden gebruikt in een browser om inhoud weer te geven. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Controleert of codering kan worden gebruikt in een browser om inhoud op te slaan. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Controleert of codering kan worden gebruikt in een mailclient om inhoud weer te geven. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Controleert of codering kan worden gebruikt in een mailclient om inhoud op te slaan. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Controleert of codering alleen-lezen is. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Controleert of codering één byte is. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Haalt Latin1-codering op. VOOR INTERN GEBRUIK. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Haalt het standaard Unicode-coderingsobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Haalt het standaard UTF-7-coderingsobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Haalt het standaard UTF-8-coderingsobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Alleen intern, te gebruiken door de bibliotheekklassen: Niet gemarkeerd en niet-invoervalidatie. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Haalt IANA-compatibele coderingsnaam op. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Haalt [Windows](../../system.windows/) codepagina-ID op. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Haal het aantal tekens op dat nodig is om een tekenbuffer te coderen. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Haal het aantal tekens op dat nodig is om een tekenbuffer te coderen. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Haal het aantal tekens op dat nodig is om een tekenbuffer te coderen. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Haal het aantal tekens op dat nodig is om een string te coderen. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Haal het aantal tekens op dat nodig is om een tekenbuffer te coderen. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Haal het aantal tekens op dat nodig is om een tekenbuffer te coderen. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Haal de bytes op die voortkomen uit het coderen van een tekenbuffer. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Haal het aantal tekens op dat nodig is om een byte-buffer te decoderen. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Haal het aantal tekens op dat nodig is om een byte-buffer te decoderen. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Haal het aantal tekens op dat nodig is om een byte-buffer te decoderen. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Haal de tekens op die voortkomen uit het decoderen van een byte-buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Haal de tekens op die voortkomen uit het decoderen van een byte-buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Haal de tekens op die voortkomen uit het decoderen van een byte-buffer. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Haal de tekens op die voortkomen uit het decoderen van een byte-buffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Haal een decoder op die verzoeken doorstuurt naar dit object. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Haal een encoder op die verzoeken doorstuurt naar dit object. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Haalt codering op op naam. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Haalt codering op op codepagina. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Haalt codering op op codepagina. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Haalt codering op op naam. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Haalt lijst van bekende coderingen op. |
| int [GetHashCode](./gethashcode/)() const override | Hasht codering. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Haal het maximum aantal bytes op dat nodig is om een opgegeven aantal tekens te coderen. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Haal het maximum aantal tekens op dat nodig is om een opgegeven aantal bytes te decoderen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Retourneert een reeks bytes die de codering aanduidt (bijv. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Decodeert een byte-buffer naar een string. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Decodeert een byte-buffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodeert een byte-buffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodeert een byte-buffer naar een string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodeert een byte-buffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodeert een byte-buffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodeert een byte-buffer naar een string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodeert een byte-buffer naar een string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge aan C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge aan C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Direct aanroepen of [LockContext](../../system/lockcontext/)-bewakingsobject gebruiken. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge aan C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert alleen nieuw object en stelt subklassen in staat om gekopieerd te worden. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen nieuw object en stelt subklassen in staat om gekopieerd te worden. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergeleken objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergeleken objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel waarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met opgegeven waarde. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Stelt decoderfallback in. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Stelt encoderfallback in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als zwakke pointer (in plaats van gedeelde). Maakt wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge aan C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Direct aanroepen of [LockContext](../../system/lockcontext/)-bewakingsobject gebruiken. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Standaard codepagina-waarde. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Text](../)
* Bibliotheek [Aspose.Slides](../../)