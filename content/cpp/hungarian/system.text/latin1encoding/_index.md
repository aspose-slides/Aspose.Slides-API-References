---
title: Latin1Encoding
second_title: Aspose.Slides C++ API Referencia
description: "Latin1 kódolás támogatás. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mert futásidejű hibákat és/vagy állítási hibákat eredményezhet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként történő függvényhíváshoz."
type: docs
weight: 313
url: /hu/system.text/latin1encoding/
---
## Latin1Encoding osztály


Latin1 kódolás támogatás. Ennek az osztálynak az objektumai csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével allokálhatók. Soha ne hozza létre ennek a típusnak az példányát a stacken vagy az operator new-val, mert futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként.

```cpp
class Latin1Encoding : public System::Text::ICUEncoding
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | Klónozza a kódolási objektumot. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Átalakítja a bájtokat két kódolás között. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Átalakítja a bájtokat két kódolás között. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Összehasonlítja a kódolásokat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Lekéri az ASCII kódolást. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Lekéri a szabványos big-endian Unicode kódolási objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Lekéri a szabványos big-endian UTF-32 kódolási objektumot. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Lekéri a levelező ügynök törzséhez kompatibilis kódolás nevét. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Lekéri a [Windows](../../system.windows/) kódlap azonosítót. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Lekéri a dekóder tartalékot. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Lekéri az alapértelmezett kódolást. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Lekéri az enkóder tartalékot. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Lekéri az ember által olvasható kódolás nevet. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Lekéri a levelező ügynök fejléchez kompatibilis kódolás nevet. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Ellenőrzi, hogy a kódolás használható-e böngészőben a tartalom megjelenítéséhez. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Ellenőrzi, hogy a kódolás használható-e böngészőben a tartalom mentéséhez. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Ellenőrzi, hogy a kódolás használható-e levelező kliensben a tartalom megjelenítéséhez. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Ellenőrzi, hogy a kódolás használható-e levelező kliensben a tartalom mentéséhez. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Ellenőrzi, hogy a kódolás csak olvasható-e. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Ellenőrzi, hogy a kódolás egybájtos-e. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Lekéri a Latin1 kódolást. CSAK BELSO HASZNÁLATRA. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Lekéri a szabványos Unicode kódolási objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Lekéri a szabványos UTF-7 kódolási objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Lekéri a szabványos UTF-8 kódolási objektumot. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Csak belső, a osztálykönyvtárak által használható: Jelöletlen és nem bemenet-ellenőrző. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Lekéri az IANA-kompatibilis kódolás nevet. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Lekéri a [Windows](../../system.windows/) kódlap azonosítót. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Megkapja a karakterpuffer kódolásához szükséges karakterek számát. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Lekéri azokat a bájtokat, amelyek a karakterpuffer kódolásából származnak. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Megkapja a bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Megkapja a bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Megkapja a bájtpuffer dekódolásához szükséges karakterek számát. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Megkapja a bájtpuffer dekódolásához szükséges karakterek számát. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Lekéri a bájtpuffer dekódolásából eredő karaktereket. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Lekéri a bájtpuffer dekódolásából eredő karaktereket. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Lekéri a bájtpuffer dekódolásából eredő karaktereket. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Lekéri a bájtpuffer dekódolásából eredő karaktereket. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Lekéri a bájtpuffer dekódolásából eredő karaktereket. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz rendelt referencia számoló adatstruktúrát. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Lekéri egy dekódert, amely a kéréseket erre az objektumra irányítja. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Lekéri egy enkódert, amely a kéréseket erre az objektumra irányítja. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Lekéri a kódolást név alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Lekéri a kódolást kódlap alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Lekéri a kódolást kódlap alapján. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Lekéri a kódolást név alapján. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Lekéri az ismert kódolások listáját. |
| int [GetHashCode](../encoding/gethashcode/)() const override | Kódolás hash-ét számítja. |
| int [GetMaxByteCount](../icuencoding/getmaxbytecount/)(int) override | Megkapja a megadott számú karakter kódolásához szükséges legnagyobb bájtszámot. |
| int [GetMaxCharCount](../icuencoding/getmaxcharcount/)(int) override | Megkapja a megadott számú bájt dekódolásához szükséges legnagyobb karakterek számát. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | Visszaad egy bájtsorozatot, amely a kódolást jelöli (pl. BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Dekódolja a bájtpuffer tartalmát egy karakterláncba. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekódolja a bájtpuffer tartalmát egy karakterláncba. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekódolja a bájtpuffer tartalmát egy karakterláncba. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekódolja a bájtpuffer tartalmát egy karakterláncba. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekódolja a bájtpuffer tartalmát egy karakterláncba. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekódolja a bájtpuffer tartalmát egy karakterláncba. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekódolja a bájtpuffer tartalmát egy karakterláncba. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekódolja a bájtpuffer tartalmát egy karakterláncba. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a cél típus által leírt példány-e. A C# 'is' operátor analógja. |
|  [Latin1Encoding](./latin1encoding/)() | Konstruktor. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és engedélyezi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál és engedélyezi az alosztályok másolókonstrukcióját. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Összehasonlítja a kódolásokat kódlapok használatával. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze hivatkozás alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze hivatkozás alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján hasonlítja a értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Beállítja a dekóder tartalékot. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Beállítja az enkóder tartalékot. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett) állítja. Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Megnöveli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Megnöveli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Alapértelmezett kódlap érték. |
| static constexpr [LATIN1_CODE_PAGE](./latin1_code_page/) | Kódlap. |

## Lásd még

* Osztály [ICUEncoding](../icuencoding/)
* Névterület [System::Text](../)
* Könyvtár [Aspose.Slides](../../)