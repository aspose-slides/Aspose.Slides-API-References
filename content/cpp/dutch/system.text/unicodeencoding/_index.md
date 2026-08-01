---
title: UnicodeEncoding
second_title: Aspose.Slides voor C++ API-referentie
description: "Unicode-codering. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Verpak deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om het als argument aan functies door te geven."
type: docs
weight: 339
url: /nl/system.text/unicodeencoding/
---
## UnicodeEncoding klasse

Unicode-codering. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Verpak deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om het door te geven aan functies als argument.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Dupliceert coderingobject. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Converteert bytes tussen twee coderingen. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Converteert bytes tussen twee coderingen. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt coderingen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl drijvende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl drijvende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Haalt ASCII-codering op. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Haalt het standaard big-endian Unicode-coderingobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Haalt het standaard big-endian UTF-32-coderingobject op. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Haalt mail-agent-body-compatibele coderingnaam op. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Haalt [Windows](../../system.windows/) codepagina-ID op. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Haalt decoder fallback op. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Haalt standaardcodering op. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Haalt encoder fallback op. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Haalt menselijk leesbare coderingnaam op. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Haalt mail-agent-header-compatibele coderingnaam op. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Controleert of de codering in een browser kan worden gebruikt om inhoud weer te geven. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Controleert of de codering in een browser kan worden gebruikt om inhoud op te slaan. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Controleert of de codering in een mailclient kan worden gebruikt om inhoud weer te geven. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Controleert of de codering in een mailclient kan worden gebruikt om inhoud op te slaan. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Controleert of de codering alleen-lezen is. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Controleert of de codering enkel byte is. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Haalt Latin1-codering op. VOOR INTERN GEBRUIK. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Haalt het standaard Unicode-coderingobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Haalt het standaard UTF-7-coderingobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Haalt het standaard UTF-8-coderingobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Alleen intern, te gebruiken door de klassebibliotheken: Ongemarkeerd en niet-invoervalidatie. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Haalt IANA-compatibele coderingnaam op. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Haalt [Windows](../../system.windows/) codepagina-ID op. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Bepaal het aantal tekens dat nodig is om een tekenbuffer te coderen. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Haalt de bytes op die ontstaan bij het coderen van een tekenbuffer. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Bepaal het aantal tekens dat nodig is om een byte-buffer te decoderen. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bepaal het aantal tekens dat nodig is om een byte-buffer te decoderen. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bepaal het aantal tekens dat nodig is om een byte-buffer te decoderen. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Bepaal het aantal tekens dat nodig is om een byte-buffer te decoderen. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Haalt de tekens op die ontstaan bij het decoderen van een byte-buffer. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Haalt de tekens op die ontstaan bij het decoderen van een byte-buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Haalt de tekens op die ontstaan bij het decoderen van een byte-buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Haalt de tekens op die ontstaan bij het decoderen van een byte-buffer. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Haalt de tekens op die ontstaan bij het decoderen van een byte-buffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Haalt een decoder op die verzoeken doorstuurt naar dit object. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Haalt een encoder op die verzoeken doorstuurt naar dit object. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Haalt codering op op naam. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Haalt codering op op codepagina. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Haalt codering op op codepagina. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Haalt codering op op naam. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Haalt lijst met bekende coderingen op. |
| int [GetHashCode](./gethashcode/)() const override | Genereert hash van codering. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Bepaal het maximale aantal bytes dat nodig is om een opgegeven aantal tekens te coderen. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Bepaal het maximale aantal tekens dat nodig is om een opgegeven aantal bytes te decoderen. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | Retourneert een reeks bytes die de codering aanduidt (bijv. BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Decodeert een byte-buffer naar een string. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Decodeert een byte-buffer naar een string. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodeert een byte-buffer naar een string. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodeert een byte-buffer naar een string. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodeert een byte-buffer naar een string. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodeert een byte-buffer naar een string. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodeert een byte-buffer naar een string. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodeert een byte-buffer naar een string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Constructor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type dat wordt beschreven door targetType is. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| **bool** [operator==](./operator_equal_equal/)(const [UnicodeEncoding](./)\&) const | Vergelijkt coderingen op codepagina's en vlaggen. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Vergelijkt coderingen met codepagina's. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert gedeelde referentieteller met opgegeven waarde. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Stelt decoder fallback in. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Stelt encoder fallback in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n'th sjabloon-argument in als zwakke pointer (in plaats van gedeelde). Stelt overschakelen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
|  [UnicodeEncoding](./unicodeencoding/)() | Constructor. |
|  [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**) | Constructor. |
|  [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**, **bool**) | Constructor. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | Big-endian codepagina-nummer. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standaard codepagina-waarde. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | Little-endian codepagina-nummer. |

## Zie ook

* Klasse [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Bibliotheek [Aspose.Slides](../../)