---
title: ICUEncoding
second_title: "Aspose.Slides for C++ API Referencia"
description: "ICU-alapú kódolási megvalósítás. CSUPÁN BELSŐ HASZNÁLATRA. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel runtime hibákat és/vagy assertion hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek."
type: docs
weight: 300
url: /hu/system.text/icuencoding/
---
## ICUEncoding osztály

ICU-alapú kódolási megvalósítás. CSUPÁN BELSŐ HASZNÁLATRA. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel runtime hibákat és/vagy assertion hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek.

```cpp
class ICUEncoding : public System::Text::Encoding
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | Klónozza a kódoló objektumot. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Átalakítja a bájtokat két kódolás között. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Átalakítja a bájtokat két kódolás között. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Összehasonlítja a kódolásokat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Visszaadja az ASCII kódolást. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Visszaadja a szabványos big-endian Unicode kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Visszaadja a szabványos big-endian UTF-32 kódoló objektumot. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Visszaadja a levelező ügynök törzséhez kompatibilis kódolás nevét. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Visszaadja a [Windows](../../system.windows/) kódlap azonosítót. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Visszaadja a dekóder tartalékértékét. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Visszaadja az alapértelmezett kódolást. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Visszaadja a kóder tartalékértékét. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Visszaadja az ember által olvasható kódolás nevet. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Visszaadja a levelező ügynök fejléchez kompatibilis kódolás nevét. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Ellenőrzi, hogy a kódolás használható-e a böngészőben a tartalom megjelenítésére. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Ellenőrzi, hogy a kódolás használható-e a böngészőben a tartalom mentésére. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Ellenőrzi, hogy a kódolás használható-e a levélkliensekben a tartalom megjelenítésére. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Ellenőrzi, hogy a kódolás használható-e a levélkliensekben a tartalom mentésére. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Ellenőrzi, hogy a kódolás csak olvasható-e. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Ellenőrzi, hogy a kódolás egybájtos-e. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Visszaadja a Latin1 kódolást. CSUPÁN BELSŐ HASZNÁLATRA. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Visszaadja a szabványos Unicode kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Visszaadja a szabványos UTF-7 kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Visszaadja a szabványos UTF-8 kódoló objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Csak belső, a osztálykönyvtárak által használt: Jelöletlen és nem bemenet-ellenőrző. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Visszaadja az IANA-kompatibilis kódolás nevét. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Visszaadja a [Windows](../../system.windows/) kódlap azonosítót. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | Megkapja a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | Megkapja a karakterpuffer kódolásából származó bájtokat. |
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
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | Megkapja a bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Megkapja a bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Megkapja a bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Megkapja a bájtpuffer dekódolásához szükséges karakterek számát. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | Megkapja a bájtpuffer dekódolásából származó karaktereket. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Megkapja a bájtpuffer dekódolásából származó karaktereket. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Megkapja a bájtpuffer dekódolásából származó karaktereket. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Megkapja a bájtpuffer dekódolásából származó karaktereket. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Megkapja a bájtpuffer dekódolásából származó karaktereket. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | Visszaad egy dekódert, amely a kéréseket erre az objektumra irányítja. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | Visszaad egy kódert, amely a kéréseket erre az objektumra irányítja. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Visszaadja a kódolást név alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Visszaadja a kódolást kódlap alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Visszaadja a kódolást kódlap alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Visszaadja a kódolást név alapján. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Visszaadja a ismert kódolások listáját. |
| int [GetHashCode](../encoding/gethashcode/)() const override | Hash-eli a kódolást. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Megkapja a megadott számú karakter kódolásához szükséges maximális bájtok számát. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Megkapja a megadott számú bájt dekódolásához szükséges maximális karakterek számát. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | Visszaad egy bájtsorozatot, amely jelzi a kódolást (pl. BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Dekódolja a bájtpuffert egy stringgé. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekódolja a bájtpuffert egy stringgé. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekódolja a bájtpuffert egy stringgé. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekódolja a bájtpuffert egy stringgé. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekódolja a bájtpuffert egy stringgé. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekódolja a bájtpuffert egy stringgé. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekódolja a bájtpuffert egy stringgé. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekódolja a bájtpuffert egy stringgé. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| **bool** [operator==](./operator_equal_equal/)(const [ICUEncoding](./)\&) const | Összehasonlítja a kódolásokat kódlapok alapján. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Beállítja a dekóder tartalékértékét. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Beállítja a kóder tartalékértékét. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonparamétert gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Alapértelmezett kódlap érték. |

## Lásd még

* Osztály [Encoding](../encoding/)
* Névterület [System::Text](../)
* Könyvtár [Aspose.Slides](../../)