---
title: UTF7Encoding
second_title: Referensi API Aspose.Slides untuk C++
description: "Pengkodean UTF-7. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 365
url: /id/system.text/utf7encoding/
---
## UTF7Encoding kelas

Pengkodean UTF-7. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Menyalin objek encoding. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Mengonversi byte antara dua encoding. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Mengonversi byte antara dua encoding. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Membandingkan dengan objek. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Mendapatkan encoding ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Mendapatkan objek encoding Unicode big-endian standar. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Mendapatkan objek encoding UTF-32 big-endian standar. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Mendapatkan nama encoding yang kompatibel dengan badan agen surat. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Mendapatkan ID codepage [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Mendapatkan fallback decoder. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Mendapatkan encoding default. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Mendapatkan fallback encoder. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Mendapatkan nama encoding yang dapat dibaca manusia. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Mendapatkan nama encoding yang kompatibel dengan header agen surat. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Memeriksa apakah encoding dapat digunakan di peramban untuk menampilkan konten. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Memeriksa apakah encoding dapat digunakan di peramban untuk menyimpan konten. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Memeriksa apakah encoding dapat digunakan di klien surat untuk menampilkan konten. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Memeriksa apakah encoding dapat digunakan di klien surat untuk menyimpan konten. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Memeriksa apakah encoding bersifat baca-saja. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Memeriksa apakah encoding berukuran satu byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Mendapatkan encoding Latin1. UNTUK PENGGUNAAN INTERNAL. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Mendapatkan objek encoding Unicode standar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Mendapatkan objek encoding UTF-7 standar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Mendapatkan objek encoding UTF-8 standar. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Hanya internal, untuk digunakan oleh pustaka kelas: Tidak ditandai dan tidak memvalidasi masukan. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Mendapatkan nama encoding yang kompatibel dengan IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Mendapatkan ID codepage [Windows](../../system.windows/). |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | Mendapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Mendapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Mendapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Mendapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Mendapatkan jumlah karakter yang diperlukan untuk mengenkode sebuah string. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Mendapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Mendapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Mendapatkan byte yang dihasilkan dari pengenkodean buffer karakter. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Mendapatkan jumlah karakter yang diperlukan untuk mendekode buffer byte. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | Mendapatkan jumlah karakter yang diperlukan untuk mendekode buffer byte. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Mendapatkan jumlah karakter yang diperlukan untuk mendekode buffer byte. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Mendapatkan jumlah karakter yang diperlukan untuk mendekode buffer byte. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Mendapatkan jumlah karakter yang diperlukan untuk mendekode buffer byte. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | Mendapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | Mendapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Mendapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Mendapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Mendapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Mendapatkan karakter yang dihasilkan dari mendekode buffer byte. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | Mendapatkan decoder yang meneruskan permintaan ke objek ini. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | Mendapatkan encoder yang meneruskan permintaan ke objek ini. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Mendapatkan encoding berdasarkan nama. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Mendapatkan encoding berdasarkan codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Mendapatkan encoding berdasarkan codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Mendapatkan encoding berdasarkan nama. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Mendapatkan daftar encoding yang dikenal. |
| int [GetHashCode](./gethashcode/)() const override | Mendapatkan kode hash encoding. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Mendapatkan jumlah maksimum byte yang diperlukan untuk mengenkode jumlah karakter tertentu. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Mendapatkan jumlah maksimum karakter yang diperlukan untuk mendekode jumlah byte tertentu. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | Mengembalikan urutan byte yang menunjukkan encoding (mis. BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Mendekode buffer byte menjadi string. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Mendekode buffer byte menjadi string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Mendekode buffer byte menjadi string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Mendekode buffer byte menjadi string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Mendekode buffer byte menjadi string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan penyalinan tipe khusus. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | Membandingkan parameter encoding. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Mengatur fallback decoder. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Mengatur fallback encoder. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengkonversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| [UTF7Encoding](./utf7encoding/)() | Konstruktor. |
| [UTF7Encoding](./utf7encoding/)(**bool**) | Konstruktor. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan weak reference. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan weak reference. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Nilai default codepage. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Angka ajaib yang digunakan oleh [Windows](../../system.windows/) untuk ID codepage UTF-7. |

## Lihat Juga

* Kelas [Encoding](../encoding/)
* Ruang Nama [System::Text](../)
* Pustaka [Aspose.Slides](../../)