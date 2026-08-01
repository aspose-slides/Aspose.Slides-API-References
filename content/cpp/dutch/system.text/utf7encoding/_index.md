---
title: UTF7Encoding
second_title: Aspose.Slides voor C++ API-referentie
description: "UTF-7 codering. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 365
url: /nl/system.text/utf7encoding/
---
## UTF7Encoding klasse

UTF-7 codering. Objecten van deze klasse mogen alleen worden toegewezen met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Kopieert het coderingobject. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Converteert bytes tussen twee coderingen. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Converteert bytes tussen twee coderingen. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt met object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Haalt ASCII-codering op. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Haalt het standaard big-endian Unicode-codering object op. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Haalt het standaard big-endian UTF-32-codering object op. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Haalt de mail-agent-lichaam-compatibele coderingsnaam op. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Haalt [Windows](../../system.windows/) codepage-id op. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Haalt decoder fallback op. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Haalt standaardcodering op. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Haalt encoder fallback op. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Haalt menselijk leesbare coderingsnaam op. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Haalt de mail-agent-header-compatibele coderingsnaam op. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Controleert of codering kan worden gebruikt in een browser om inhoud weer te geven. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Controleert of codering kan worden gebruikt in een browser om inhoud op te slaan. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Controleert of codering kan worden gebruikt in een mailclient om inhoud weer te geven. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Controleert of codering kan worden gebruikt in een mailclient om inhoud op te slaan. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Controleert of codering alleen-lezen is. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Controleert of codering één byte is. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Haalt Latin1-codering op. ENKEL VOOR INTERNE GEBRUIK. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Haalt het standaard Unicode-codering object op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Haalt het standaard UTF-7-codering object op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Haalt het standaard UTF-8-codering object op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Alleen intern, te gebruiken door de klassbibliotheken: Niet gemarkeerd en niet-input-validerend. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Haalt IANA-compatibele coderingsnaam op. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Haalt [Windows](../../system.windows/) codepage-id op. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | Bepaal het aantal tekens dat nodig is om een tekenbuffer te encoderen. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Bepaal het aantal tekens dat nodig is om een tekenbuffer te encoderen. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Bepaal het aantal tekens dat nodig is om een tekenbuffer te encoderen. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Bepaal het aantal tekens dat nodig is om een tekenbuffer te encoderen. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Bepaal het aantal tekens dat nodig is om een string te encoderen. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Bepaal het aantal tekens dat nodig is om een tekenbuffer te encoderen. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Bepaal het aantal tekens dat nodig is om een tekenbuffer te encoderen. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Bepaal de bytes die voortkomen uit het encoderen van een tekenbuffer. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Bepaal het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | Bepaal het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bepaal het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bepaal het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Bepaal het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | Bepaal de tekens die voortkomen uit het decoderen van een bytebuffer. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | Bepaal de tekens die voortkomen uit het decoderen van een bytebuffer. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Bepaal de tekens die voortkomen uit het decoderen van een bytebuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bepaal de tekens die voortkomen uit het decoderen van een bytebuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bepaal de tekens die voortkomen uit het decoderen van een bytebuffer. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Bepaal de tekens die voortkomen uit het decoderen van een bytebuffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die aan het object is gekoppeld. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | Haalt een decoder op die verzoeken doorstuurt naar dit object. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | Haalt een encoder op die verzoeken doorstuurt naar dit object. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Haalt codering op op naam. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Haalt codering op op codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Haalt codering op op codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Haalt codering op op naam. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Haalt lijst van bekende coderingen op. |
| int [GetHashCode](./gethashcode/)() const override | Haalt coderingshashcode op. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Bepaal het maximale aantal bytes dat nodig is om een opgegeven aantal tekens te encoderen. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Bepaal het maximale aantal tekens dat nodig is om een opgegeven aantal bytes te decoderen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | Retourneert een reeks bytes die de codering aangeeft (bijv. BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Decodeert een bytebuffer naar een string. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodeert een bytebuffer naar een string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodeert een bytebuffer naar een string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodeert een bytebuffer naar een string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analogie van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analogie van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachtoobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Constructor. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructeur. Kopieert eigenlijk niets, initialiseert alleen nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | Vergelijkt coderingsparameters. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie-waarde type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentietelling met opgegeven waarde. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Stelt decoder fallback in. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Stelt encoder fallback in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n'th sjabloonargument in als zwakke pointer (in plaats van gedeelde). Maakt schakelen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentietelling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentietelling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachtoobject. |
|  [UTF7Encoding](./utf7encoding/)() | Constructor. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | Constructor. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentietelling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentietelling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standaard codepage-waarde. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Magisch getal gebruikt door [Windows](../../system.windows/) voor UTF-7 codepage-id. |

## Zie ook

* Klasse [Encoding](../encoding/)
* Naamruimte [System::Text](../)
* Bibliotheek [Aspose.Slides](../../)