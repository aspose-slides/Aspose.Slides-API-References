---
title: String
second_title: Referensi API Aspose.Slides untuk C++
description: "Kelas String digunakan di seluruh perpustakaan. Merupakan pengganti System.String C# saat menerjemahkan kode. Untuk alasan optimasi, tidak dianggap sebagai subclass Object. Tipe ini harus dialokasikan pada stack dan dilewatkan ke fungsi oleh nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 1275
url: /id/system/string/
---
## Kelas String


[String](./) kelas yang digunakan di seluruh perpustakaan. Merupakan pengganti untuk C# [System.String](./) saat menerjemahkan kode. Karena alasan optimasi, tidak dianggap sebagai subclass [Object](../object/). Tipe ini harus dialokasikan di stack dan dilewatkan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek tipe ini.

```cpp
class String
```

## Metode

| Method | Description |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) adalah tipe nilai di sisi C++ yang secara implisit (tanpa pewarisan) mengimplementasikan beberapa antarmuka. |
| const UChar * [begin](./begin/)() const | Mengembalikan pointer ke awal buffer string yang sebenarnya. Tidak pernah melakukan alokasi ulang apapun. Tidak menjamin buffer berakhir dengan null. |
| [String](./) [Clone](./clone/)() const | Membuat salinan dari string saat ini. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Membandingkan dua substring dengan operator kurang-sama-lebih. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Membandingkan dua substring dengan operator kurang-sama-lebih. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Membandingkan dua string dengan operator kurang-sama-lebih. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Membandingkan dua string dengan operator kurang-sama-lebih. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Membandingkan dua string dengan operator kurang-sama-lebih. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Membandingkan dua string dengan operator kurang-sama-lebih. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Membandingkan dua string dengan operator kurang-sama-lebih menggunakan mode ordinal. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Membandingkan dua string dengan operator kurang-sama-lebih menggunakan mode ordinal. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Membandingkan dua string dengan gaya 'kurang-sama-lebih'. Menggunakan budaya (culture) saat ini. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Menggabungkan string. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Menggabungkan string. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Menggabungkan string. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Menggabungkan string. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Memeriksa apakah str merupakan substring dari string saat ini. |
| **bool** [Contains](./contains/)(char16_t) const | Memeriksa apakah string berisi karakter yang diberikan. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Membuat salinan string. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Menyalin karakter string ke elemen array yang sudah ada. Tidak melakukan perubahan ukuran. |
| const UChar * [end](./end/)() const | Mengembalikan pointer ke akhir buffer string yang sebenarnya. Tidak pernah melakukan alokasi ulang apapun. Tidak menjamin buffer berakhir dengan null. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Memeriksa apakah string berakhir dengan substring yang ditentukan. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Memeriksa apakah string berakhir dengan substring yang ditentukan. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Memeriksa apakah string berakhir dengan substring yang ditentukan. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Perbandingan kesetaraan [String](./). Beberapa mode yang disediakan oleh enumerasi StringComparison didukung. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | Perbandingan kesetaraan [String](./). Menggunakan mode perbandingan [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Membandingkan kesetaraan dua string menggunakan mode perbandingan Ordial. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Membandingkan kesetaraan dua string. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Mencoba mengonversi sebuah [String](./) ke string ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Memformat string gaya C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Memformat string gaya C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Memformat string gaya C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Memformat string gaya C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Memformat string gaya C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Membuat [String](./) dari string ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Membuat [String](./) dari string ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Membuat [String](./) dari string ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Membuat [String](./) dari string utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Membuat [String](./) dari string utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Membuat [String](./) dari string utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Membuat [String](./) dari string utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Membuat [String](./) dari string utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Membuat [String](./) dari string utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Membuat [String](./) dari widestring. |
| int [get_Length](./get_length/)() const | Mendapatkan panjang string. |
| int [GetHashCode](./gethashcode/)() const | Menghasilkan hash dari string yang berisi. Diimplementasikan dalam ICU, tidak cocok dengan hash di C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Pencarian maju substring. |
| int [IndexOf](./indexof/)(char_t, int) const | Pencarian maju karakter. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Pencarian maju karakter dalam substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Pencarian maju substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Pencarian maju substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Pencarian maju substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Pencarian maju substring. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Pencarian maju karakter. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Secara berurutan mencari semua karakter str dalam ini. Jika karakter pertama ditemukan, posisinya dikembalikan, jika tidak maka mencari karakter kedua, dan seterusnya. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Mencari salah satu karakter yang diberikan di seluruh string. Membandingkan karakter pertama string dengan semua karakter di anyOf, kemudian karakter kedua, dan seterusnya. Mengembalikan indeks karakter pertama yang cocok dengan salah satu target. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Mencari salah satu karakter yang diberikan dalam substring. Membandingkan karakter pertama string dengan semua karakter di anyOf, kemudian karakter kedua, dan seterusnya. Mengembalikan indeks karakter pertama yang cocok dengan salah satu target. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Mencari salah satu karakter yang diberikan dalam substring. Membandingkan karakter pertama string dengan semua karakter di anyOf, kemudian karakter kedua, dan seterusnya. Mengembalikan indeks karakter pertama yang cocok dengan salah satu target. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Menyisipkan substring pada posisi yang ditentukan. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek string bertipe yang ditentukan oleh [TypeInfo](../typeinfo/) yang diberikan. |
| **bool** [IsAsciiString](./isasciistring/)() const | Menunjukkan apakah sebuah [String](./) hanya berisi simbol ASCII. |
| **bool** [IsEmpty](./isempty/)() const | Memeriksa apakah string tidak null dan kosong. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Memeriksa apakah string unicode dinormalisasi menggunakan bentuk normalisasi yang ditentukan. |
| **bool** [IsNull](./isnull/)() const | Memeriksa apakah string dianggap null. [String](./) adalah null hanya jika dibangun melalui konstruktor [String()](./string/), dipindahkan, disalin atau ditetapkan dari string null atau metode [reset()](./reset/) dipanggil. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Memeriksa apakah string kosong atau dianggap null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Memeriksa apakah string yang diberikan null atau kosong. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Menunjukkan apakah string yang ditentukan null, kosong, atau hanya berisi karakter spasi putih. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Menggabungkan array menggunakan string sebagai pemisah. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Menggabungkan array menggunakan string sebagai pemisah. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Menggabungkan array menggunakan string sebagai pemisah. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Menggabungkan array menggunakan string sebagai pemisah. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Pencarian mundur substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Pencarian mundur substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Pencarian mundur substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Pencarian mundur substring. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Pencarian mundur karakter. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Pencarian mundur karakter. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Pencarian mundur karakter. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Mencari salah satu karakter yang diberikan di seluruh string secara mundur. Membandingkan karakter terakhir string dengan semua karakter di anyOf, kemudian karakter sebelumnya, dan seterusnya. Mengembalikan indeks kecocokan pertama yang ditemukan. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Mencari salah satu karakter yang diberikan dalam substring secara mundur. Membandingkan karakter terakhir string dengan semua karakter di anyOf, kemudian karakter sebelumnya, dan seterusnya. Mengembalikan indeks kecocokan pertama yang ditemukan. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Mencari salah satu karakter yang diberikan dalam substring secara mundur. Membandingkan karakter terakhir string dengan semua karakter di anyOf, kemudian karakter sebelumnya, dan seterusnya. Mengembalikan indeks kecocokan pertama yang ditemukan. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Menormalisasi string unicode menggunakan bentuk normalisasi yang ditentukan. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Mengonversi string menjadi span hanya-baca. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Operator perbandingan tidak sama. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Memeriksa apakah string tidak null. Menerapkan logika yang sama seperti panggilan [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | Operator penggabungan [String](./). |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Penggabungan [String](./) dengan literal string atau pointer string karakter. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Menambahkan karakter ke akhir string. |
| [String](./) [operator+](./operator_plus/)(int) const | Menambahkan representasi string nilai integer ke akhir string. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Menambahkan representasi string nilai unsigned integer ke akhir string. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Menambahkan representasi string nilai floating point ke akhir string. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Menambahkan representasi string nilai integer ke akhir string. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Menambahkan representasi string objek tipe referensi ke akhir string. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Menambahkan representasi string objek tipe referensi ke akhir string. |
| [String](./) [operator+](./operator_plus/)(T) const | Menambahkan representasi string nilai boolean ke akhir string. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Operator penugasan penggabungan. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Operator penugasan penggabungan. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Operator penugasan penggabungan. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Operator penugasan penggabungan. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Operator penugasan konkatenasi. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Operator penugasan konkatenasi. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Operator penugasan konkatenasi. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Operator penugasan konkatenasi. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Operator penugasan konkatenasi. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Operator penugasan konkatenasi. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Operator penugasan konkatenasi. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Membandingkan urutan string. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Operator penugasan. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Operator penugasan pindah. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Operator perbandingan kesetaraan. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Memeriksa apakah string bernilai null. Menerapkan logika yang sama seperti panggilan [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Membandingkan urutan string. |
| char_t [operator[]](./operator[]/)(int) const | Mendapatkan karakter pada posisi yang ditentukan. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Menambahkan padding di sebelah kiri string asli. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Menambahkan padding di sebelah kanan string asli. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Mengembalikan iterator terbalik ke karakter terakhir (jika ada) dari buffer string aktual. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Mengekstrak semua kecuali substring dari string saat ini. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Mengembalikan iterator terbalik ke posisi sebelum karakter pertama (jika ada) dari buffer string aktual. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Mengganti semua kemunculan karakter dalam string. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Mengganti semua kemunculan pencarian dalam string ini. |
| [String](./)\& [reset](./reset/)() | Mengatur string menjadi null. Sama dengan 'string_variable_name = null' di C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Mengatur karakter pada posisi yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan karakter. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan karakter. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan salah satu dari dua karakter. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan salah satu karakter yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan salah satu karakter yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Membagi string berdasarkan substring. Saat ini, hanya mendukung array pemisah dengan nol atau satu elemen. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Memeriksa apakah string dimulai dengan substring yang ditentukan. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Memeriksa apakah string dimulai dengan substring yang ditentukan. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Memeriksa apakah string dimulai dengan substring yang ditentukan. |
|  [String](./string/)() | Konstruktor default. Membuat objek string yang dianggap null. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Membuat string berdasarkan literal string. Menganggap literal sebagai string berakhiran null, menghitung panjang string target berdasarkan ukuran literal. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Membuat string berdasarkan penunjuk string karakter. Menganggap string yang ditunjuk berakhiran null, menghitung panjang string target berdasarkan karakter null. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Membuat string berdasarkan literal string. Menganggap literal sebagai string berakhiran null dalam UTF8, menghitung panjang string target berdasarkan ukuran literal. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Membuat string berdasarkan penunjuk string karakter. Menganggap string yang ditunjuk berakhiran null dalam UTF8, menghitung panjang string target berdasarkan karakter null. |
|  [String](./string/)(const char16_t *, int) | Membuat string dari penunjuk string karakter dan panjang eksplisit. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Menginisialisasi instansi baru dari kelas [System.String](./) ke karakter Unicode yang ditunjukkan dalam rentang hanya-baca yang ditentukan. |
|  [String](./string/)(const char *, int) | Membuat string dari penunjuk string karakter dan panjang eksplisit. |
|  [String](./string/)(const char16_t *, int, int) | Membuat string dari penunjuk string karakter mulai dari posisi awal menggunakan panjang. |
| explicit  [String](./string/)(const char16_t, int) | Konstruktor pengisian. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Konstruktor nullptr. Dideklarasikan sebagai templat untuk menyelesaikan prioritas dengan konstruktor templat lainnya. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Membuat string berdasarkan literal widestring. Menganggap literal sebagai string berakhiran null, menghitung panjang string target berdasarkan ukuran literal. Konversi dari **wchar_t** memakan waktu pada beberapa platform, sehingga konversi implisit tidak diizinkan. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Membuat string berdasarkan penunjuk string karakter lebar. Menganggap string yang ditunjuk berakhiran null, menghitung panjang string target berdasarkan karakter null. Konversi dari **wchar_t** memakan waktu pada beberapa platform, sehingga konversi implisit tidak diizinkan. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Membuat string dari penunjuk string karakter lebar dan panjang eksplisit. Konversi dari **wchar_t** memakan waktu pada beberapa platform, sehingga konversi implisit tidak diizinkan. |
| explicit  [String](./string/)(const **wchar_t**, int) | Konstruktor pengisian. Konversi dari **wchar_t** memakan waktu pada beberapa platform, sehingga konversi implisit tidak diizinkan. |
|  [String](./string/)(const [String](./)\&) | Konstruktor penyalin. |
|  [String](./string/)([String](./)\&&) | Konstruktor pindah. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Mengonversi seluruh array karakter menjadi string. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Mengonversi subrentang array karakter menjadi string. Jika parameter berada di luar batas array, string kosong akan dibuat. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Membungkus UnicodeString ke dalam [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Konstruktor pindah. |
| explicit  [String](./string/)(const std::wstring\&) | Membuat [String](./) dari widestring. |
| explicit  [String](./string/)(const std::u16string\&) | Membuat [String](./) dari string utf16. |
| explicit  [String](./string/)(const std::string\&) | Membuat [String](./) dari string std::string yang disajikan dalam format UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Membuat [String](./) dari string std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Mengekstrak substring. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Mengekstrak substring. |
| std::string [ToAsciiString](./toasciistring/)() const | Mengonversi string ke std::string. Menggunakan enkoding ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Mengonversi string atau substring menjadi array byte. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Mengonversi string atau substring menjadi array karakter. |
| [String](./) [ToLower](./tolower/)() const | Mengonversi semua karakter string menjadi huruf kecil. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Mengonversi semua karakter string menjadi huruf kecil menggunakan budaya tertentu. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Mengonversi semua karakter string menjadi huruf kecil menggunakan budaya invarian. |
| [String](./) [ToString](./tostring/)() const | Pembungkus untuk menangani kelas [String](./) dalam konteks dimana [ToString()](./tostring/) dipanggil pada objek tipe nilai. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Pembungkus untuk menangani kelas [String](./) dalam konteks dimana [ToString()](./tostring/) dipanggil pada objek tipe nilai. |
| std::u16string [ToU16Str](./tou16str/)() const | Mengonversi string ke std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Mengonversi string ke std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Mengonversi semua karakter string menjadi huruf besar. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Mengonversi semua karakter string menjadi huruf besar menggunakan budaya tertentu. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Mengonversi semua karakter string menjadi huruf besar menggunakan budaya invarian. |
| std::string [ToUtf8String](./toutf8string/)() const | Mengonversi string ke std::string. Menggunakan enkoding UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Mengonversi string ke std::wstring. |
| [String](./) [Trim](./trim/)() const | Menghapus semua karakter spasi putih dari awal dan akhir string. |
| [String](./) [Trim](./trim/)(char_t) const | Menghapus semua kemunculan karakter yang diberikan dari awal dan akhir string. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Menghapus semua kemunculan karakter yang diberikan dari awal dan akhir string. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Menghapus semua kemunculan karakter yang diberikan dari awal dan akhir string. |
| [String](./) [TrimEnd](./trimend/)() const | Menghapus semua karakter spasi putih dari akhir string. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Menghapus semua kemunculan karakter yang diberikan dari akhir string. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Menghapus semua kemunculan karakter yang diberikan dari akhir string. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Menghapus semua kemunculan karakter yang diberikan dari akhir string. |
| [String](./) [TrimStart](./trimstart/)() const | Menghapus semua karakter spasi putih dari awal string. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Menghapus semua kemunculan karakter yang diberikan dari awal string. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Menghapus semua kemunculan karakter yang diberikan dari awal string. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Menghapus semua kemunculan karakter yang diberikan dari awal string. |
| const UChar * [u_str](./u_str/)() const | Mengembalikan buffer null-terminated bergaya ICU. Mungkin akan mengalokasikan ulang string. |
|  [~String](./~string/)() | Destruktor. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | String kosong. |
| static [Null](./null/) | String null. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Tipe iterator terbalik. |
## Catatan



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Bangun string dari array karakter dan cetak.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Bangun string dari array byte dan cetak.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Potong string di bawah ini dan cetak.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Cetak jumlah kata dalam .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
hello
world
"String ini berisi spasi putih di awal dan di akhir."
Number of words: 11
*/
```

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)