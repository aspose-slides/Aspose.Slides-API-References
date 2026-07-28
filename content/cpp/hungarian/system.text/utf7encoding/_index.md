---
title: UTF7Encoding
second_title: Aspose.Slides C++ API referencia
description: "UTF-7 kódolás. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt a veremben vagy a new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadáshoz a függvényeknek."
type: docs
weight: 365
url: /hu/system.text/utf7encoding/
---
## UTF7Encoding osztály

UTF-7 kódolás. Ennek az osztálynak a példányait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt a veremben vagy a new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásra.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klónozza a kódolási objektumot. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Átkonvertálja a bájtokat két kódolás között. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Átkonvertálja a bájtokat két kódolás között. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Összehasonlít egy objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze az objektumokat. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Lekéri az ASCII kódolást. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Lekéri a szabványos nagy-endián Unicode kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Lekéri a szabványos nagy-endián UTF-32 kódoló objektumot. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Lekéri a levelező ügynök törzséhez kompatibilis kódolás nevét. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Lekéri a [Windows](../../system.windows/) kódlap-azonosítót. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Lekéri a dekóder tartalékát. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Lekéri az alapértelmezett kódolást. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Lekéri a kódoló tartalékát. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Lekéri az ember által olvasható kódolás nevét. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Lekéri a levelező ügynök fejlécéhez kompatibilis kódolás nevét. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Ellenőrzi, hogy a kódolás használható-e a böngészőben a tartalom megjelenítéséhez. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Ellenőrzi, hogy a kódolás használható-e a böngészőben a tartalom mentéséhez. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Ellenőrzi, hogy a kódolás használható-e a levelező kliensben a tartalom megjelenítéséhez. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Ellenőrzi, hogy a kódolás használható-e a levelező kliensben a tartalom mentéséhez. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Ellenőrzi, hogy a kódolás csak olvasható-e. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Ellenőrzi, hogy a kódolás egybájtos-e. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Lekéri a Latin1 kódolást. FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Lekéri a szabványos Unicode kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Lekéri a szabványos UTF-7 kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Lekéri a szabványos UTF-8 kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Csak belső használatra, a osztálykönyvtárak által: jelöletlen és nem bemenet-ellenőrző. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Lekéri az IANA-kompatibilis kódolás nevét. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Lekéri a [Windows](../../system.windows/) kódlap-azonosítót. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | Megkapja a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Megkapja a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Megkapja a karakterpuffer kódolásához szükséges karakterek számát. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Megkapja a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Megkapja a string kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Megkapja a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Megkapja a karakterpuffer kódolásához szükséges karakterek számát. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Megkapja a karakterpuffer kódolásából származó bájtokat. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Megkapja a bájtbuffer dekódolásához szükséges karakterek számát. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | Megkapja a bájtbuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Megkapja a bájtbuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Megkapja a bájtbuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Megkapja a bájtbuffer dekódolásához szükséges karakterek számát. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | Megkapja a bájtbuffer dekódolásából származó karaktereket. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | Megkapja a bájtbuffer dekódolásából származó karaktereket. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Megkapja a bájtbuffer dekódolásából származó karaktereket. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Megkapja a bájtbuffer dekódolásából származó karaktereket. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Megkapja a bájtbuffer dekódolásából származó karaktereket. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Megkapja a bájtbuffer dekódolásából származó karaktereket. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | Lekér egy dekódert, amely a kéréseket továbbítja ehhez az objektumhoz. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | Lekér egy kódolót, amely a kéréseket továbbítja ehhez az objektumhoz. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Lekéri a kódolást név alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Lekéri a kódolást kódlap alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Lekéri a kódolást kódlap alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Lekéri a kódolást név alapján. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Lekéri a ismert kódolások listáját. |
| int [GetHashCode](./gethashcode/)() const override | Lekéri a kódolás hash kódját. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Megkapja a megadott számú karakter kódolásához szükséges maximális bájtok számát. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Megkapja a megadott számú bájt dekódolásához szükséges maximális karakterek számát. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | Visszaad egy bájtsorozatot, amely a kódolást jelöli (pl. BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Dekódol egy bájtpufferből egy stringet. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Dekódol egy bájtpufferből egy stringet. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekódol egy bájtpufferből egy stringet. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekódol egy bájtpufferből egy stringet. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekódol egy bájtpufferből egy stringet. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekódol egy bájtpufferből egy stringet. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekódol egy bájtpufferből egy stringet. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekódol egy bájtpufferből egy stringet. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekódol egy bájtpufferből egy stringet. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a megadott targetType típusú példány-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolását. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | Összehasonlítja a kódolások paramétereit. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciaként. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciaként. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Beállítja a dekóder tartalékát. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Beállítja a kódoló tartalékát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók gyengévé alakítását konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okosmutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okosmutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
|  [UTF7Encoding](./utf7encoding/)() | Konstruktor. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | Konstruktor. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okosmutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okosmutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Alapértelmezett kódlap érték. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Mágikus szám, amelyet a [Windows](../../system.windows/) használ a UTF-7 kódlap azonosítójához. |

## Lásd még

* Osztály [Encoding](../encoding/)
* Névtere [System::Text](../)
* Könyvtár [Aspose.Slides](../../)