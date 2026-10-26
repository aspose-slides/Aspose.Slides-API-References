---
title: Encoding
second_title: Referensi API Aspose.Slides untuk C++
description: Layanan encoding.
type: docs
weight: 222
url: /id/system.text/encoding/
---
## Kelas Encoding

[Encoding](./) layanan.

```cpp
class Encoding : public System::Object
```

## Metode

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Mengkloning objek encoding. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Mengonversi byte antara dua encoding. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Mengonversi byte antara dua encoding. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Membandingkan encoding. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk penggunaan internal. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Mendapatkan encoding ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Mendapatkan objek encoding Unicode big-endian standar. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Mendapatkan objek encoding UTF-32 big-endian standar. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Mendapatkan nama encoding yang kompatibel dengan badan agen email. |
| virtual int [get_CodePage](./get_codepage/)() | Mendapatkan [Windows](../../system.windows/) ID halaman kode. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Mendapatkan fallback decoder. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Mendapatkan encoding default. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Mendapatkan fallback encoder. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Mendapatkan nama encoding yang dapat dibaca manusia. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Mendapatkan nama encoding yang kompatibel dengan header agen email. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Memeriksa apakah encoding dapat digunakan di peramban untuk menampilkan konten. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Memeriksa apakah encoding dapat digunakan di peramban untuk menyimpan konten. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Memeriksa apakah encoding dapat digunakan di klien email untuk menampilkan konten. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Memeriksa apakah encoding dapat digunakan di klien email untuk menyimpan konten. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Memeriksa apakah encoding bersifat baca-saja. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Memeriksa apakah encoding berukuran satu byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Mendapatkan encoding Latin1. UNTUK PENGGUNAAN INTERNAL. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Mendapatkan objek encoding Unicode standar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Mendapatkan objek encoding UTF-7 standar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Mendapatkan objek encoding UTF-8 standar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Hanya internal, untuk digunakan oleh perpustakaan kelas: Tidak ditandai dan tidak memvalidasi input. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Mendapatkan nama encoding yang kompatibel dengan IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Mendapatkan [Windows](../../system.windows/) ID halaman kode. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Dapatkan jumlah karakter yang diperlukan untuk meng-encode buffer karakter. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Dapatkan jumlah karakter yang diperlukan untuk meng-encode buffer karakter. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Dapatkan jumlah karakter yang diperlukan untuk meng-encode buffer karakter. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Dapatkan jumlah karakter yang diperlukan untuk meng-encode string. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Dapatkan jumlah karakter yang diperlukan untuk meng-encode buffer karakter. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Dapatkan jumlah karakter yang diperlukan untuk meng-encode buffer karakter. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Dapatkan byte yang dihasilkan dari meng-encode buffer karakter. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dapatkan jumlah karakter yang diperlukan untuk mendekode buffer byte. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dapatkan jumlah karakter yang diperlukan untuk mendekode buffer byte. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Dapatkan jumlah karakter yang diperlukan untuk mendekode buffer byte. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Dapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Dapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Mendapatkan decoder yang meneruskan permintaan ke objek ini. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Mendapatkan encoder yang meneruskan permintaan ke objek ini. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Mendapatkan encoding berdasarkan nama. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Mendapatkan encoding berdasarkan halaman kode. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Mendapatkan encoding berdasarkan halaman kode. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Mendapatkan encoding berdasarkan nama. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Mendapatkan daftar encoding yang dikenal. |
| int [GetHashCode](./gethashcode/)() const override | Membuat hash encoding. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Dapatkan jumlah maksimum byte yang diperlukan untuk meng-encode sejumlah karakter tertentu. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Dapatkan jumlah maksimum karakter yang diperlukan untuk mendekode sejumlah byte tertentu. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Mengembalikan urutan byte yang menunjukkan encoding (mis. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Mendekode buffer byte menjadi string. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Mendekode buffer byte menjadi string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Mendekode buffer byte menjadi string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Mendekode buffer byte menjadi string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan pengkloningan tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak benar-benar menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak benar-benar menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama oleh nilai yang ditentukan. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Mengatur fallback decoder. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Mengatur fallback encoder. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil secara langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil secara langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Nilai halaman kode default. |

## Alias Tipe

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [System::Text](../)
* Pustaka [Aspose.Slides](../../)