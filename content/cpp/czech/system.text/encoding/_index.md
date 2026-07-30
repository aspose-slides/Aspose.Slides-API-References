---
title: Encoding
second_title: Aspose.Slides pro C++ referenční příručka API
description: Služby kódování.
type: docs
weight: 222
url: /cs/system.text/encoding/
---
## Encoding třída


[Encoding](./) služby.
```cpp
class Encoding : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Vytvoří klon objektu kódování. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Převádí bajty mezi dvěma kódováními. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Převádí bajty mezi dvěma kódováními. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porovnává kódování. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Získá kódování ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Získá standardní objekt kódování Unicode s velkým endianem. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Získá standardní objekt kódování UTF-32 s velkým endianem. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Získá název kódování kompatibilní s tělem poštovního agenta. |
| virtual int [get_CodePage](./get_codepage/)() | Získá ID kódové stránky [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Získá záložní dekodér. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Získá výchozí kódování. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Získá záložní enkodér. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Získá čitelný název kódování. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Získá název kódování kompatibilní s hlavičkou poštovního agenta. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Kontroluje, zda lze kódování použít v prohlížeči k vykreslení obsahu. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Kontroluje, zda lze kódování použít v prohlížeči k uložení obsahu. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Kontroluje, zda lze kódování použít v poštovním klientovi k vykreslení obsahu. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Kontroluje, zda lze kódování použít v poštovním klientovi k uložení obsahu. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Kontroluje, zda je kódování pouze pro čtení. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Kontroluje, zda je kódování jednojbytové. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Získá kódování Latin1. PRO INTERNÍ POUŽITÍ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Získá standardní objekt kódování Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Získá standardní objekt kódování UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Získá standardní objekt kódování UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Pouze interní, má být používáno knihovnami třídy: neoznačené a nevalidující vstup. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Získá název kódování kompatibilní s IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Získá ID kódové stránky [Windows](../../system.windows/). |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Získá počet znaků potřebných k zakódování vyrovnávací paměti znaků. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Získá počet znaků potřebných k zakódování vyrovnávací paměti znaků. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Získá počet znaků potřebných k zakódování vyrovnávací paměti znaků. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Získá počet znaků potřebných k zakódování řetězce. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Získá počet znaků potřebných k zakódování vyrovnávací paměti znaků. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Získá počet znaků potřebných k zakódování vyrovnávací paměti znaků. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Získá bajty vzniklé zakódováním vyrovnávací paměti znaků. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Získá počet znaků potřebných k dekódování vyrovnávací paměti bajtů. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Získá počet znaků potřebných k dekódování vyrovnávací paměti bajtů. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Získá počet znaků potřebných k dekódování vyrovnávací paměti bajtů. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Získá znaky vzniklé dekódováním vyrovnávací paměti bajtů. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Získá znaky vzniklé dekódováním vyrovnávací paměti bajtů. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Získá znaky vzniklé dekódováním vyrovnávací paměti bajtů. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Získá znaky vzniklé dekódováním vyrovnávací paměti bajtů. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače spojenou s objektem. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Získá dekodér, který přeposílá požadavky tomuto objektu. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Získá enkodér, který přeposílá požadavky tomuto objektu. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Získá kódování podle názvu. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Získá kódování podle kódové stránky. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Získá kódování podle kódové stránky. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Získá kódování podle názvu. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Získá seznam známých kódování. |
| int [GetHashCode](./gethashcode/)() const override | Vytvoří hash kódování. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Získá maximální počet bajtů potřebných k zakódování zadaného počtu znaků. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Získá maximální počet znaků potřebných k dekódování zadaného počtu bajtů. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Vrátí sekvenci bajtů, která označuje kódování (např. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Dekóduje vyrovnávací paměť bajtů do řetězce. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekóduje vyrovnávací paměť bajtů do řetězce. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekóduje vyrovnávací paměť bajtů do řetězce. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekóduje vyrovnávací paměť bajtů do řetězce. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekóduje vyrovnávací paměť bajtů do řetězce. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekóduje vyrovnávací paměť bajtů do řetězce. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekóduje vyrovnávací paměť bajtů do řetězce. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekóduje vyrovnávací paměť bajtů do řetězce. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() prohlášení. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Nastaví záložní dekodér. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Nastaví záložní enkodér. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock() prohlášení. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Pole

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Výchozí hodnota kódové stránky. |

## Typedefy

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Text](../)
* Knihovna [Aspose.Slides](../../)