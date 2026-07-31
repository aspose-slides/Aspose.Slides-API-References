---
title: TimeSpan
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili interval waktu. Tipe ini harus dialokasikan pada stack dan dipassing ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek jenis ini."
type: docs
weight: 1314
url: /id/system/timespan/
---
## Kelas TimeSpan

Mewakili interval waktu. Tipe ini harus dialokasikan pada stack dan dipassing ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek jenis ini.

```cpp
class TimeSpan
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Mengembalikan sebuah instance baru dari kelas [TimeSpan](./) yang mewakili interval waktu yang merupakan penjumlahan dari interval waktu yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Membandingkan dua objek [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Membandingkan objek saat ini dan objek yang ditentukan. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Membandingkan objek saat ini dan objek yang ditentukan. |
| [TimeSpan](./) [Duration](./duration/)() const | Mengembalikan sebuah instance baru dari objek [TimeSpan](./) yang nilainya adalah nilai absolut dari objek saat ini. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Menentukan apakah interval waktu yang diwakili oleh objek saat ini sama dengan interval waktu yang diwakili oleh objek yang ditentukan. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Menentukan apakah interval waktu yang diwakili oleh objek saat ini sama dengan interval waktu yang diwakili oleh objek yang ditentukan. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Mengembalikan true jika objek yang ditentukan mewakili interval waktu yang sama, jika tidak - false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Mengembalikan sebuah objek [TimeSpan](./) baru yang mewakili interval yang ditentukan. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Mengembalikan sebuah objek [TimeSpan](./) baru yang mewakili interval yang ditentukan. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Mengembalikan sebuah objek [TimeSpan](./) baru yang mewakili interval yang ditentukan. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Mengembalikan sebuah objek [TimeSpan](./) baru yang mewakili interval yang ditentukan. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Mengembalikan sebuah objek [TimeSpan](./) baru yang mewakili interval yang ditentukan. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Mengembalikan sebuah objek [TimeSpan](./) baru yang mewakili interval yang ditentukan. |
| constexpr int [get_Days](./get_days/)() const | Mengembalikan komponen hari dari interval waktu yang diwakili oleh objek [TimeSpan](./) saat ini. |
| constexpr int [get_Hours](./get_hours/)() const | Mengembalikan komponen jam dari interval waktu yang diwakili oleh objek [TimeSpan](./) saat ini. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Mengembalikan komponen milidetik dari interval waktu yang diwakili oleh objek [TimeSpan](./) saat ini. |
| constexpr int [get_Minutes](./get_minutes/)() const | Mengembalikan komponen menit dari interval waktu yang diwakili oleh objek [TimeSpan](./) saat ini. |
| constexpr int [get_Seconds](./get_seconds/)() const | Mengembalikan komponen detik dari interval waktu yang diwakili oleh objek [TimeSpan](./) saat ini. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Mengembalikan jumlah interval 100-nanodetik yang membentuk interval waktu yang diwakili oleh objek [TimeSpan](./) saat ini. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Mengembalikan nilai objek [TimeSpan](./) saat ini yang diekspresikan dalam hari penuh dan pecahan. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Mengembalikan nilai objek [TimeSpan](./) saat ini yang diekspresikan dalam jam penuh dan pecahan. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Mengembalikan nilai objek [TimeSpan](./) saat ini yang diekspresikan dalam milidetik penuh dan pecahan. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Mengembalikan nilai objek [TimeSpan](./) saat ini yang diekspresikan dalam menit penuh dan pecahan. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Mengembalikan nilai objek [TimeSpan](./) saat ini yang diekspresikan dalam detik penuh dan pecahan. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Mengembalikan sebuah instance baru dari objek [TimeSpan](./) yang mewakili nilai negatif yang diwakili oleh objek [TimeSpan](./) saat ini. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Menentukan apakah interval waktu yang diwakili oleh objek saat ini tidak sama dengan interval waktu yang diwakili oleh objek yang ditentukan. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Mengembalikan sebuah instance baru dari kelas [TimeSpan](./) yang mewakili interval waktu yang merupakan penjumlahan dari interval waktu yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Mengembalikan diri sendiri. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Menetapkan ke objek saat ini interval waktu yang merupakan penjumlahan dari interval waktu yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Mengembalikan sebuah instance baru dari kelas [TimeSpan](./) yang mewakili interval waktu yang merupakan hasil pengurangan interval waktu yang diwakili oleh objek yang ditentukan dari interval waktu yang diwakili oleh objek saat ini. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Mengembalikan sebuah instance baru dari objek [TimeSpan](./) yang mewakili nilai negatif yang diwakili oleh objek [TimeSpan](./) saat ini. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Menetapkan ke objek saat ini interval waktu yang merupakan hasil pengurangan interval waktu yang diwakili oleh objek yang ditentukan dari interval waktu yang diwakili oleh objek saat ini. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Menentukan apakah interval waktu yang diwakili oleh objek saat ini lebih pendek daripada interval waktu yang diwakili oleh objek yang ditentukan. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Menentukan apakah interval waktu yang diwakili oleh objek saat ini lebih pendek atau sama dengan interval waktu yang diwakili oleh objek yang ditentukan. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Mengatur interval waktu yang diwakili oleh objek [TimeSpan](./) yang ditentukan menjadi objek [TimeSpan](./) saat ini. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Menentukan apakah interval waktu yang diwakili oleh objek saat ini sama dengan interval waktu yang diwakili oleh objek yang ditentukan. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Menentukan apakah interval waktu yang diwakili oleh objek saat ini lebih panjang daripada interval waktu yang diwakili oleh objek yang ditentukan. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Menentukan apakah interval waktu yang diwakili oleh objek saat ini lebih panjang atau sama dengan interval waktu yang diwakili oleh objek yang ditentukan. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Mengonversi string ke objek [TimeSpan](./) yang setara. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string ke objek [TimeSpan](./) yang setara menggunakan penyedia format yang ditentukan. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Mengonversi string ke objek [TimeSpan](./) yang setara menggunakan format, penyedia format, dan gaya yang ditentukan. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Mengonversi string ke objek [TimeSpan](./) yang setara menggunakan format, penyedia format, dan gaya yang ditentukan. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Mengembalikan sebuah instance baru dari kelas [TimeSpan](./) yang mewakili interval waktu yang merupakan hasil pengurangan interval waktu yang diwakili oleh objek yang ditentukan dari interval waktu yang diwakili oleh objek saat ini. |
| constexpr [TimeSpan](./timespan/)() | Membuat sebuah objek [TimeSpan](./) yang mewakili interval waktu nol. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Membuat sebuah instance dari kelas [TimeSpan](./) yang mewakili interval waktu yang ditentukan. |
|  [TimeSpan](./timespan/)(int, int, int) | Membuat sebuah instance dari kelas [TimeSpan](./) yang mewakili interval waktu yang sama dengan jumlah jam, menit, dan detik yang ditentukan. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Membuat sebuah instance dari kelas [TimeSpan](./) yang mewakili interval waktu yang sama dengan jumlah jam, menit, detik, dan milidetik yang ditentukan. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Membuat sebuah objek [TimeSpan](./) yang mewakili interval waktu yang sama dengan interval waktu yang diwakili oleh objek [TimeSpan](./) yang ditentukan. |
| [String](../string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari interval waktu yang diwakili oleh objek saat ini. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Mengonversi nilai objek saat ini ke representasi string yang setara, menggunakan format yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengonversi nilai objek saat ini ke representasi string yang setara, menggunakan format dan penyedia format yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Mengonversi string ke objek [TimeSpan](./) yang setara dan mengembalikan hasil konversi. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Mengonversi string ke objek [TimeSpan](./) yang setara menggunakan penyedia format yang ditentukan dan mengembalikan hasil konversi. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Mengonversi string ke objek [TimeSpan](./) yang setara menggunakan format, penyedia format, dan mengembalikan hasil konversi. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Mengonversi string ke objek [TimeSpan](./) yang setara menggunakan format, penyedia format, dan gaya yang ditentukan, serta mengembalikan hasil konversi. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Mengonversi string ke objek [TimeSpan](./) yang setara menggunakan format, penyedia format, dan gaya yang ditentukan, serta mengembalikan hasil konversi. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Mengonversi string ke objek [TimeSpan](./) yang setara menggunakan format dan penyedia format, serta mengembalikan hasil konversi. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Mengembalikan sebuah objek [TypeInfo](../typeinfo/) yang mewakili struktur [TimeSpan](./). |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [MaxValue](./maxvalue/) | Objek [TimeSpan](./) yang mewakili interval terpanjang yang mungkin. |
| static [MinValue](./minvalue/) | /// Objek [TimeSpan](./) yang mewakili interval terpendek yang mungkin. |
| static constexpr [TicksPerDay](./ticksperday/) | Jumlah interval 100-nanodetik dalam satu hari (interval 24 jam). |
| static constexpr [TicksPerHour](./ticksperhour/) | Jumlah interval 100-nanodetik dalam satu jam. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Jumlah interval 100-nanodetik dalam satu milidetik. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Jumlah interval 100-nanodetik dalam satu menit. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Jumlah interval 100-nanodetik dalam satu detik. |
| static [Zero](./zero/) | Objek [TimeSpan](./) yang mewakili interval nol. |

## Catatan

```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Jumlah tick: 260928000000000
Jumlah milidetik: 0
Jumlah total milidetik: 2.60928e+10
Jumlah menit: 0
Jumlah total menit: 434880
Jumlah jam: 0
Jumlah total jam: 0
Jumlah hari: 302
Jumlah total hari: 302
*/
```

## Lihat Juga

* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)