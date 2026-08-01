---
title: ASCIIEncoding
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt ASCII-codering voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Pak deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 1
url: /nl/system.text/asciiencoding/
---
## ASCIIEncoding klasse


Stelt ASCII-codering voor. Objecten van deze klasse moeten alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Gebruik altijd deze klasse verpakt in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [ASCIIEncoding](./asciiencoding/)() | Constructor. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | Kloont een coderingobject. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Converteert bytes tussen twee coderingen. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Converteert bytes tussen twee coderingen. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt coderingen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietypeobjecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Verkrijgt ASCII-codering. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Verkrijgt het standaard big-endian Unicode-coderingobject. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Verkrijgt het standaard big-endian UTF-32-coderingobject. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Haalt mailagent-body compatibele coderingnaam op. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Haalt [Windows](../../system.windows/) codepagina-ID op. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Haalt decoder fallback op. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Haalt standaardcodering op. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Haalt encoder fallback op. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Haalt menselijk leesbare coderingnaam op. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Haalt mailagent-header compatibele coderingnaam op. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Controleert of codering kan worden gebruikt in een browser om inhoud weer te geven. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Controleert of codering kan worden gebruikt in een browser om inhoud op te slaan. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Controleert of codering kan worden gebruikt in een mailclient om inhoud weer te geven. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Controleert of codering kan worden gebruikt in een mailclient om inhoud op te slaan. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Controleert of codering alleen-lezen is. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Controleert of codering enkelbyte is. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Haalt Latin1-codering op. VOOR INTERN GEBRUIK. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Haalt het standaard Unicode-coderingobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Haalt het standaard UTF-7-coderingobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Haalt het standaard UTF-8-coderingobject op. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Alleen intern, te gebruiken door de klassenbibliotheken: Ongeëtiketteerd en niet-invoer-validerend. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Haalt IANA-compatibele coderingnaam op. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Haalt [Windows](../../system.windows/) codepagina-ID op. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Haal het aantal tekens dat nodig is om een tekenbuffer te coderen. |
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
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Haalt het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Haalt het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Haalt het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Haalt het aantal tekens dat nodig is om een bytebuffer te decoderen. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Haalt de tekens op die ontstaan bij het decoderen van een bytebuffer. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Haalt de tekens op die ontstaan bij het decoderen van een bytebuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Haalt de tekens op die ontstaan bij het decoderen van een bytebuffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Haalt de tekens op die ontstaan bij het decoderen van een bytebuffer. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Haalt de tekens op die ontstaan bij het decoderen van een bytebuffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-structuur op die bij het object hoort. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Haalt een decoder op die verzoeken doorstuurt naar dit object. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Haalt een encoder op die verzoeken doorstuurt naar dit object. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Haalt codering op op naam. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Haalt codering op op codepagina. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Haalt codering op op codepagina. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Haalt codering op op naam. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Haalt lijst van bekende coderingen op. |
| int [GetHashCode](../encoding/gethashcode/)() const override | Hash de codering. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Haalt maximale byte-aantal op dat mogelijk is voor een string met een bekend aantal tekens. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Haalt het maximale aantal tekens dat nodig is om een gespecificeerd aantal bytes te decoderen. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | Retourneert een reeks bytes die de codering aanduidt (bijv. BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Decodeert een bytebuffer naar een string. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodeert een bytebuffer naar een string. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodeert een bytebuffer naar een string. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodeert een bytebuffer naar een string. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodeert een bytebuffer naar een string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Constructor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Direct aanroepen of gebruik [LockContext](../../system/lockcontext/) toezichthouderobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, echt, initialiseert alleen nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen nieuw object en maakt kopiëren van subklassen mogelijk. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Vergelijkt coderingen met behulp van codepagina's. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie van waardetypeobject met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Stelt decoder fallback in. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Stelt encoder fallback in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel n'th sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Direct aanroepen of gebruik [LockContext](../../system/lockcontext/) toezichthouderobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standaard codepagina-waarde. |

## Zie ook

* Klasse [ICUEncoding](../icuencoding/)
* Naamruimte [System::Text](../)
* Bibliotheek [Aspose.Slides](../../)