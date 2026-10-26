---
title: Char
second_title: Aspose.Slides for C++ API referenciája
description: Metódusokat biztosít a UTF-16 kódegységeként reprezentált karakterek manipulálásához. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha ne hozzon létre példányt ebből semmilyen módon.
type: docs
weight: 170
url: /hu/system/char/
---
## Char osztály

Metódusokat biztosít a UTF-16 kódegységeként reprezentált karakterek manipulálásához. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha ne hozzon létre példányt ebből semmilyen módon.

```cpp
class Char
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Átalakítja a UTF-32 kódegységet egy [System::String](../string/) osztály példányává. |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Átalakítja a megadott UTF-16 szurrogát párost UTF-32 kódegységgé. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Átalakítja egy UTF-16 kódolású karakter vagy szurrogát pár adott pozícióban egy karakterláncban lévő értékét UTF-32 kódegységgé. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Átalakítja a megadott UTF-16 karaktert dupla pontosságú lebegőpontos numerikus értékké. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Visszaad egy értéket, amely a megadott karakter Unicode kategóriáját reprezentálja. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Megállapítja, hogy a megadott karakter ASCII szóközkarakternek minősül-e. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter Unicode vezérlőkarakternek minősül-e. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Megállapítja, hogy a megadott karakter Unicode vezérlőkarakternek minősül-e. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter tizedes számjegynek minősül-e. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter tizedes számjegynek minősül-e. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Megállapítja, hogy a megadott karakter tizedes számjegynek minősül-e. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Megállapítja, hogy a megadott karakterláncban a megadott indexen lévő karakter UTF-16 magas szurrogát kódegység-e. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter magas szurrogát-e. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Megállapítja, hogy a megadott karakter magas szurrogát-e. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter Unicode betűnek minősül-e. |
| static **bool** [IsLetter](./isletter/)(char_t) | Megállapítja, hogy a megadott karakter Unicode betűnek minősül-e. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter Unicode betű vagy tizedes számjegynek minősül-e. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Megállapítja, hogy a megadott karakter Unicode betű vagy tizedes számjegynek minősül-e. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter kisbetűnek minősül-e. |
| static **bool** [IsLower](./islower/)(char_t) | Megállapítja, hogy a megadott karakter kisbetűnek minősül-e. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Megállapítja, hogy a megadott karakterláncban a megadott indexen lévő karakter kisbetűnek minősül-e. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter alacsony szurrogát-e. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Megállapítja, hogy a megadott karakter alacsony szurrogát-e. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter számnak minősül-e. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Megállapítja, hogy a megadott karakter számnak minősül-e. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter írásjelnek minősül-e. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Megállapítja, hogy a megadott karakter írásjelnek minősül-e. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpbufferben a megadott indexen lévő karakter elválasztó karakternek minősül-e. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Megállapítja, hogy a megadott karakter elválasztó karakternek minősül-e. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Megállapítja, hogy a megadott karakter UTF-16 szurrogát kódegység-e. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Megállapítja, hogy a megadott karakterláncban a megadott indexen lévő karakter UTF-16 szurrogát kódegység-e. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Megállapítja, hogy a megadott két karakter UTF-16 szurrogát párt alkot-e. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Megállapítja, hogy a megadott karakterpufferben két egymást követő karakter szurrogát párt alkot-e. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter szimbólumkarakternek minősül-e. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Megállapítja, hogy a megadott karakter szimbólumkarakternek minősül-e. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Megállapítja, hogy a megadott karakterláncban a megadott indexen lévő karakter nagybetűnek minősül-e. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter nagybetűnek minősül-e. |
| static **bool** [IsUpper](./isupper/)(char_t) | Megállapítja, hogy a megadott karakter nagybetűnek minősül-e. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Megállapítja, hogy a megadott karakterpufferben a megadott indexen lévő karakter szóközkarakternek minősül-e. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Megállapítja, hogy a megadott karakter szóközkarakternek minősül-e. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Megállapítja, hogy a megadott karakterláncban a megadott indexen lévő karakter szóközkarakternek minősül-e. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterlánc első és egyetlen karakterét char_t értékké. |
| static char_t [ToLower](./tolower/)(char_t) | Átalakítja a megadott karaktert kisbetűssé. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Átalakítja a megadott karaktert kisbetűssé. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Átalakítja a megadott karaktert kisbetűssé. |
| static char_t [ToUpper](./toupper/)(char_t) | Átalakítja a megadott karaktert nagybetűssé. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Átalakítja a megadott karaktert nagybetűssé. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Átalakítja a megadott karaktert nagybetűssé. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Megpróbálja egyetlen karakterből álló karakterláncot UTF-16 karakterré konvertálni. A függvény csak akkor sikerül, ha a bemeneti karakterlánc nem null és pontosan egy karakter hosszú. |

## Lásd még

* Namespace [System](../)
* Library [Aspose.Slides](../../)