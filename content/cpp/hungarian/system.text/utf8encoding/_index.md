---
title: UTF8Encoding
second_title: Aspose.Slides C++ API referencia
description: "UTF-8 kódolás. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból veremben vagy az new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként funkcióknak való átadásra."
type: docs
weight: 378
url: /hu/system.text/utf8encoding/
---
## UTF8Encoding osztály

UTF-8 kódolás. Az osztály példányait csak a(z) [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból veremben vagy az new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvényeknek való argumentumként való átadásra.

```cpp
class UTF8Encoding : public System::Text::ICUEncoding
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klónozza a kódolás objektumot. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Átalakítja a bájtokat két kódolás között. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Átalakítja a bájtokat két kódolás között. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Összehasonlítja egy objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Ugyancsóz a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Ugyancsóz a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célra. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII kódolást ad vissza. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | A szabványos nagy-endian Unicode kódolás objektumát adja vissza. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | A szabványos nagy-endian UTF-32 kódolás objektumát adja vissza. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | A levélügynök törzsének kompatibilis kódolás nevét adja vissza. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | A(z) [Windows](../../system.windows/) kódlap azonosítót adja vissza. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Dekóder visszaesést ad vissza. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Alapértelmezett kódolást ad vissza. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Kódoló visszaesést ad vissza. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Emberek számára olvasható kódolás nevet ad vissza. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | A levélügynök fejlécével kompatibilis kódolás nevet ad vissza. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Ellenőrzi, hogy a kódolás használható-e böngészőben a tartalom megjelenítéséhez. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Ellenőrzi, hogy a kódolás használható-e böngészőben a tartalom mentéséhez. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Ellenőrzi, hogy a kódolás használható-e e-mail kliensben a tartalom megjelenítéséhez. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Ellenőrzi, hogy a kódolás használható-e e-mail kliensben a tartalom mentéséhez. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Ellenőrzi, hogy a kódolás csak olvasható-e. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Ellenőrzi, hogy a kódolás egybájtos-e. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 kódolást ad vissza. BELÉN HASZNÁLATHOZ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | A szabványos Unicode kódolás objektumát adja vissza. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | A szabványos UTF-7 kódolás objektumát adja vissza. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | A szabványos UTF-8 kódolás objektumát adja vissza. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Csak belső használatra, az osztálykönyvtárak által: jelöletlen és nem bemenet-ellenőrző. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA-kompatibilis kódolás nevet ad vissza. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | A(z) [Windows](../../system.windows/) kódlap azonosítót adja vissza. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | A karakterpuffer kódolásához szükséges karakterek számát adja vissza. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | A bájtok számát adja vissza, amelyek a karakterpuffer kódolásából származnak. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | A bájtpuffer dekódolásához szükséges karakterek számát adja vissza. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | A bájtpuffer dekódolásához szükséges karakterek számát adja vissza. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | A bájtpuffer dekódolásához szükséges karakterek számát adja vissza. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | A bájtpuffer dekódolásához szükséges karakterek számát adja vissza. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | A karaktereket adja vissza, amelyek a bájtpuffer dekódolásából származnak. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | A karaktereket adja vissza, amelyek a bájtpuffer dekódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | A karaktereket adja vissza, amelyek a bájtpuffer dekódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | A karaktereket adja vissza, amelyek a bájtpuffer dekódolásából származnak. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | A karaktereket adja vissza, amelyek a bájtpuffer dekódolásából származnak. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz tartozó referencia számláló adatstruktúrát adja vissza. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Egy dekódert ad, amely a kéréseket továbbítja ehhez az objektumhoz. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Egy kódolót ad, amely a kéréseket továbbítja ehhez az objektumhoz. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Név alapján adja vissza a kódolást. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Kódlap alapján adja vissza a kódolást. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Kódlap alapján adja vissza a kódolást. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Név alapján adja vissza a kódolást. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | A ismert kódolások listáját adja vissza. |
| int [GetHashCode](./gethashcode/)() const override | A kódolás hash kódját adja vissza. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Megadja a megadott számú karakter kódolásához szükséges maximális bájtok számát. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Megadja a megadott számú bájt dekódolásához szükséges maximális karakterek számát. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | Kódlap preambulumot ad vissza. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Dekódol egy bájtpufferet stringgé. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekódol egy bájtpufferet stringgé. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekódol egy bájtpufferet stringgé. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekódol egy bájtpufferet stringgé. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekódol egy bájtpufferet stringgé. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekódol egy bájtpufferet stringgé. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekódol egy bájtpufferet stringgé. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekódol egy bájtpufferet stringgé. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példányát képviseli-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a(z) [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF8Encoding](./)\&) const | Összehasonlítja a kódolások paramétereit. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Kódolásokat hasonlít össze kódlapok alapján. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Beállítja a dekóder visszaesést. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Beállítja a kódoló visszaesést. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referencia számláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a(z) [LockContext](../../system/lockcontext/) őrző objektumot. |
|  [UTF8Encoding](./utf8encoding/)() | Konstruktor. |
|  [UTF8Encoding](./utf8encoding/)(**bool**) | Konstruktor. |
|  [UTF8Encoding](./utf8encoding/)(**bool**, **bool**) | Konstruktor. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Alapértelmezett kódlap érték. |
| static constexpr [UTF8_CODE_PAGE](./utf8_code_page/) | RTTI információ. |

## Lásd még

* Osztály [ICUEncoding](../icuencoding/)
* Névtér [System::Text](../)
* Könyvtár [Aspose.Slides](../../)