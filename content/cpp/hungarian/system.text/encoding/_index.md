---
title: Encoding
second_title: Aspose.Slides C++ API-referencia
description: Kódolási szolgáltatások.
type: docs
weight: 222
url: /hu/system.text/encoding/
---
## Encoding osztály


[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Klónozza a kódolási objektumot. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Átalakítja a bájtokat két kódolás között. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Átalakítja a bájtokat két kódolás között. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Összehasonlítja a kódolásokat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Lekéri az ASCII kódolást. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Lekéri a szabványos nagyvégű Unicode kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Lekéri a szabványos nagyvégű UTF-32 kódoló objektumot. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Lekéri a levélügynök törzsnek kompatibilis kódolás nevét. |
| virtual int [get_CodePage](./get_codepage/)() | Lekéri a [Windows](../../system.windows/) kódlap azonosítót. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Lekéri a dekóder alternatív megoldását. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Lekéri az alapértelmezett kódolást. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Lekéri az enkóder alternatív megoldását. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Lekéri az ember által olvasható kódolás nevet. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Lekéri a levélügynök fejlécnek kompatibilis kódolás nevét. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Ellenőrzi, hogy a kódolás használható-e a böngészőben a tartalom megjelenítéséhez. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Ellenőrzi, hogy a kódolás használható-e a böngészőben a tartalom mentéséhez. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Ellenőrzi, hogy a kódolás használható-e a levelező kliensben a tartalom megjelenítéséhez. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Ellenőrzi, hogy a kódolás használható-e a levelező kliensben a tartalom mentéséhez. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Ellenőrzi, hogy a kódolás csak olvasható-e. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Ellenőrzi, hogy a kódolás egy bájtos-e. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Lekéri a Latin1 kódolást. FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Lekéri a szabványos Unicode kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Lekéri a szabványos UTF-7 kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Lekéri a szabványos UTF-8 kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Csak belső, az osztálykönyvtárak használják: Jelöletlen és nem-bemeneti-érvényesítő. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Lekéri az IANA-kompatibilis kódolás nevét. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Lekéri a [Windows](../../system.windows/) kódlap azonosítót. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Lekéri a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Lekéri a karakterpuffer kódolásához szükséges karakterek számát. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Lekéri a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Lekéri egy string kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Lekéri a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Lekéri a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Lekéri a karakterpuffer kódolásából származó bájtokat. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Lekéri egy bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Lekéri egy bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Lekéri egy bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Lekéri a bájtpuffer dekódolásából származó karaktereket. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Lekéri a bájtpuffer dekódolásából származó karaktereket. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Lekéri a bájtpuffer dekódolásából származó karaktereket. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Lekéri a bájtpuffer dekódolásából származó karaktereket. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Lekéri egy dekódert, amely a kéréseket erre az objektumra továbbítja. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Lekéri egy enkódert, amely a kéréseket erre az objektumra továbbítja. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Lekéri a kódolást név szerint. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Lekéri a kódolást kódlap szerint. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Lekéri a kódolást kódlap szerint. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Lekéri a kódolást név szerint. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Lekéri a ismert kódolások listáját. |
| int [GetHashCode](./gethashcode/)() const override | Hash-eli a kódolást. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Lekéri a megadott számú karakter kódolásához szükséges maximális bájtok számát. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Lekéri a megadott számú bájt dekódolásához szükséges maximális karakterek számát. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Visszaad egy bájtsorozatot, amely a kódolást jelöli (pl. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Dekódolja a bájtpuffert egy karakterláncba. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekódolja a bájtpuffert egy karakterláncba. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekódolja a bájtpuffert egy karakterláncba. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekódolja a bájtpuffert egy karakterláncba. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekódolja a bájtpuffert egy karakterláncba. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekódolja a bájtpuffert egy karakterláncba. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekódolja a bájtpuffert egy karakterláncba. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekódolja a bájtpuffert egy karakterláncba. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja az értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Beállítja a dekóder alternatív megoldását. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Beállítja az enkóder alternatív megoldását. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók tárolókban történő gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használja inkább az okos mutatókat vagy a ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használja inkább az okos mutatókat vagy a ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyéni objektumok karakterlánccá alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használja inkább az okos mutatókat vagy a ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használja inkább az okos mutatókat vagy a ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Alapértelmezett kódlap érték. |

## Typedefek

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Lásd még

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.Slides](../../)