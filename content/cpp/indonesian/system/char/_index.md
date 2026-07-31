---
title: Char
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan metode untuk memanipulasi karakter yang direpresentasikan sebagai unit kode UTF-16. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apa pun.
type: docs
weight: 170
url: /id/system/char/
---
## Kelas Char


Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Char
```

## Metode

| Method | Description |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Mengonversi unit kode UTF-32 menjadi sebuah instance dari kelas [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Mengonversi pasangan surrogate UTF-16 yang ditentukan menjadi unit kode UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Mengonversi nilai karakter yang dienkode UTF-16 atau pasangan surrogate pada posisi tertentu dalam string menjadi unit kode UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Mengonversi karakter UTF-16 yang ditentukan menjadi nilai numerik floating-point presisi ganda. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Mengembalikan nilai yang mewakili kategori Unicode dari karakter yang ditentukan. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai karakter spasi putih ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai karakter kontrol Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai karakter kontrol Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai digit desimal. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Menentukan apakah karakter pada indeks yang ditentukan dalam string yang ditentukan diklasifikasikan sebagai digit desimal. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai digit desimal. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam string yang ditentukan merupakan unit kode surrogate tinggi UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan adalah surrogate tinggi. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Menentukan apakah karakter yang ditentukan adalah surrogate tinggi. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai huruf Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai huruf Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai huruf Unicode atau digit desimal. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai huruf Unicode atau digit desimal. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai huruf kecil. |
| static **bool** [IsLower](./islower/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai huruf kecil. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam string yang ditentukan diklasifikasikan sebagai huruf kecil. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan adalah surrogate rendah. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Menentukan apakah karakter yang ditentukan adalah surrogate rendah. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai angka. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai angka. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai karakter tanda baca. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai karakter tanda baca. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai karakter pemisah. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai karakter pemisah. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Menentukan apakah karakter yang ditentukan adalah unit kode surrogate UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam string yang ditentukan adalah unit kode surrogate UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Menentukan apakah dua karakter yang ditentukan merupakan pasangan surrogate UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Menentukan apakah dua karakter berurutan dalam buffer karakter yang ditentukan merupakan pasangan surrogate. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai karakter simbol. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai karakter simbol. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam string yang ditentukan diklasifikasikan sebagai huruf kapital. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai huruf kapital. |
| static **bool** [IsUpper](./isupper/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai huruf kapital. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan diklasifikasikan sebagai karakter spasi putih. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Menentukan apakah karakter yang ditentukan diklasifikasikan sebagai karakter spasi putih. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Menentukan apakah karakter pada indeks yang ditentukan dalam string yang ditentukan diklasifikasikan sebagai karakter spasi putih. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Mengonversi karakter pertama dan satu-satunya dari string yang ditentukan menjadi nilai char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Mengonversi karakter yang ditentukan ke huruf kecil. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Mengonversi karakter yang ditentukan ke huruf kecil. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Mengonversi karakter yang ditentukan ke huruf kecil. |
| static char_t [ToUpper](./toupper/)(char_t) | Mengonversi karakter yang ditentukan ke huruf kapital. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Mengonversi karakter yang ditentukan ke huruf kapital. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Mengonversi karakter yang ditentukan ke huruf kapital. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Mencoba mengonversi string yang terdiri dari satu karakter menjadi karakter UTF-16. Fungsi berhasil hanya ketika string masukan tidak null dan memiliki panjang tepat satu karakter. |

## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)