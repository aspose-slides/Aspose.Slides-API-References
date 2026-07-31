---
title: Decimal
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili sebuah angka desimal. Tipe ini harus dialokasikan di stack dan dilewatkan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 261
url: /id/system/decimal/
---
## Decimal kelas


Mewakili sebuah angka desimal. Tipe ini harus dialokasikan di stack dan dilewatkan ke fungsi dengan nilai atau referensi. Jangan pernah gunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek tipe ini.

```cpp
class Decimal
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Menambahkan dua nilai [Decimal](./) yang ditentukan. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Mengembalikan nilai integral terkecil yang lebih besar atau sama dengan nilai yang ditentukan. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Menentukan apakah nilai yang diwakili oleh objek [Decimal](./) pertama lebih kecil, sama, atau lebih besar dari nilai yang diwakili oleh objek [Decimal](./) kedua. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih kecil, sama, atau lebih besar daripada nilai yang diwakili oleh objek yang ditentukan. |
| [Decimal](./decimal/)() | Membuat sebuah instance yang mewakili 0. |
| [Decimal](./decimal/)(std::int8_t) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(std::int16_t) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(std::int32_t) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(std::int64_t) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(std::uint8_t) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(std::uint16_t) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(std::uint32_t) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(std::uint64_t) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(**float**) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| [Decimal](./decimal/)(**double**) | Membuat sebuah instance yang mewakili nilai yang ditentukan. |
| explicit  [Decimal](./decimal/)(const std::string\&) | Membuat sebuah instance yang mewakili nilai yang representasi stringnya ditentukan sebagai sebuah instance dari kelas std::string. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Membuat objek [Decimal](./) dari komponen-komponen yang ditentukan. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Membuat sebuah instance dari kelas [Decimal](./) yang mewakili angka yang sama dengan objek [Decimal](./) yang ditentukan. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Membuat sebuah instance dari kelas [Decimal](./) dari array integer yang berisi representasi biner. |
| [Decimal](./decimal/)(std::nullptr_t) | Selalu melempar ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Membuat sebuah instance dari kelas [Decimal](./) yang mewakili nilai yang ditentukan. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Membagi dua nilai [Decimal](./) yang ditentukan. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini dan objek yang ditentukan sama. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini dan objek yang ditentukan sama. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Menentukan apakah nilai yang diwakili oleh objek-objek yang ditentukan sama. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Mengembalikan nilai integral terbesar yang kurang atau sama dengan nilai yang ditentukan. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) nilai mata uang OLE yang ditentukan ke nilai [Decimal](./) yang setara. NOT IMPLEMENTED. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Mengonversi objek [Decimal](./) yang ditentukan ke representasi biner nilai yang diwakilinya. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) nilai [Decimal](./) yang ditentukan ke array byte. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Mendapatkan kode tipe objek. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Mengalikan dua nilai [Decimal](./) yang ditentukan. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Mengembalikan sebuah instance baru dari kelas [Decimal](./) yang mewakili nilai hasil negasi nilai yang diwakili oleh objek yang ditentukan. |
| explicit  [operator bool](./operator_bool/)() const | Mengonversi nilai yang diwakili oleh objek saat ini ke nilai boolean. |
| explicit  [operator double](./operator_double/)() const | Mengonversi nilai yang diwakili oleh objek saat ini ke nilai floating-point double-precision. |
| explicit  [operator float](./operator_float/)() const | Mengonversi nilai yang diwakili oleh objek saat ini ke nilai floating-point single-precision. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini dan objek yang ditentukan tidak sama. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Menentukan apakah nilai yang diwakili oleh objek saat ini berbeda dari 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Mengembalikan sebuah instance baru dari kelas [Decimal](./) yang mewakili nilai hasil operasi modulo dengan nilai yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Menetapkan ke objek saat ini nilai baru yang merupakan hasil operasi modulo dengan nilai yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Mengembalikan sebuah instance baru dari kelas [Decimal](./) yang mewakili nilai hasil perkalian nilai yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Menetapkan ke objek saat ini nilai baru yang merupakan hasil perkalian nilai yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Mengembalikan sebuah instance baru dari kelas [Decimal](./) yang mewakili nilai yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Meningkatkan nilai yang diwakili oleh objek saat ini. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Menetapkan ke objek saat ini nilai baru yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Mengembalikan sebuah instance baru dari kelas [Decimal](./) yang mewakili nilai hasil pengurangan nilai yang diwakili oleh objek yang ditentukan dari nilai yang diwakili oleh objek saat ini. |
| [Decimal](./) [operator-](./operator_minus/)() const | Mengembalikan sebuah instance baru dari kelas [Decimal](./) yang mewakili nilai hasil negasi nilai yang diwakili oleh objek saat ini. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Mengurangi nilai yang diwakili oleh objek saat ini. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Menetapkan ke objek saat ini nilai baru yang merupakan hasil pengurangan nilai yang diwakili oleh objek yang ditentukan dari nilai yang diwakili oleh objek saat ini. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Mengembalikan sebuah instance baru dari kelas [Decimal](./) yang mewakili nilai hasil pembagian nilai yang diwakili oleh objek saat ini dengan nilai yang diwakili oleh objek yang ditentukan. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Menetapkan ke objek saat ini nilai baru yang merupakan hasil pembagian nilai yang diwakili oleh objek saat ini dengan nilai yang diwakili oleh objek yang ditentukan. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih kecil dari nilai yang diwakili oleh objek yang ditentukan. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih kecil atau sama dengan nilai yang diwakili oleh objek yang ditentukan. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Menetapkan nilai yang diwakili oleh objek yang ditentukan ke objek saat ini. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini dan objek yang ditentukan sama. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Menentukan apakah nilai yang diwakili oleh objek saat ini adalah 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar dari nilai yang diwakili oleh objek yang ditentukan. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar atau sama dengan nilai yang diwakili oleh objek yang ditentukan. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Mengonversi representasi string dari angka desimal menjadi sebuah instance setara dari kelas [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Mengonversi representasi string dari angka desimal menjadi sebuah instance setara dari kelas [Decimal](./) menggunakan gaya yang ditentukan. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi representasi string dari angka desimal menjadi sebuah instance setara dari kelas [Decimal](./) menggunakan penyedia format yang ditentukan. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi representasi string dari angka desimal menjadi sebuah instance setara dari kelas [Decimal](./) menggunakan gaya dan penyedia format yang ditentukan. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Menghitung sisa setelah membagi dua nilai [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke bilangan bulat terdekat. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama jauhnya dengan dua bilangan terdekat. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Membulatkan nilai yang ditentukan ke nilai terdekat dengan jumlah digit pecahan yang ditentukan. Sebuah parameter menentukan perilaku fungsi jika nilai yang ditentukan sama jauhnya dengan dua nilai terdekat. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Mengurangi satu nilai [Decimal](./) yang ditentukan dari nilai lainnya. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke nilai integer tak bertanda 8-bit. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke bilangan floating-point double precision. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke nilai integer bertanda 16-bit. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke nilai integer bertanda 32-bit. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke nilai integer bertanda 64-bit. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) nilai [Decimal](./) yang ditentukan ke nilai mata uang OLE yang setara. NOT IMPLEMENTED. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke nilai integer bertanda 8-bit. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke bilangan floating-point single precision. |
| std::string [ToStdString](./tostdstring/)() const | Mengembalikan sebuah instance std::string yang berisi representasi string dari nilai yang diwakili oleh objek. |
| [String](../string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari nilai yang diwakili oleh objek. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengonversi objek saat ini ke string menggunakan informasi format khusus budaya. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengonversi objek saat ini ke representasi stringnya menggunakan format string yang ditentukan dan informasi format khusus budaya yang disediakan oleh objek [IFormatProvider](../iformatprovider/) yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Mengembalikan representasi string dari nilai yang diwakili oleh objek. Untuk penggunaan internal. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke nilai integer tak bertanda 16-bit. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke nilai integer tak bertanda 32-bit. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Mengonversi nilai [Decimal](./) ke nilai integer tak bertanda 64-bit. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Mengembalikan objek [Decimal](./) yang mewakili nilai yang bagian integralnya sama dengan nilai yang diwakili oleh objek [Decimal](./) yang ditentukan dengan semua digit pecahan dibuang. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Mengonversi string yang ditentukan yang berisi representasi string angka menjadi nilai [Decimal](./) yang setara. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Mengonversi string yang ditentukan yang berisi representasi string angka menjadi nilai [Decimal](./) yang setara menggunakan informasi format dan gaya angka yang diberikan. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Mengembalikan referensi ke objek [TypeInfo](../typeinfo/) yang mewakili informasi tipe kelas [Decimal](./). |
| [~Decimal](./~decimal/)() | Destruktor. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [MaxValue](./maxvalue/) | Mewakili angka terbesar yang dapat diwakili oleh kelas [Decimal](./). |
| static [MinusOne](./minusone/) | Mewakili angka -1. |
| static [MinValue](./minvalue/) | Mewakili angka terkecil yang dapat diwakili oleh kelas [Decimal](./). |
| static [One](./one/) | Mewakili angka 1. |
| static [Zero](./zero/) | Mewakili angka 0. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [number_type](./number_type/) | Alias untuk Detail::decimal_number_type. |

## Catatan



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Lihat Juga

* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)