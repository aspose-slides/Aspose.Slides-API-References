---
title: DateTime
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili nilai tanggal dan waktu tertentu pada kontinuum waktu. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 222
url: /id/system/datetime/
---
## Kelas DateTime

Mewakili nilai tanggal dan waktu spesifik pada kontinuum waktu. Tipe ini harus dialokasikan di stack dan diberikan ke fungsi secara nilai atau referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek dari tipe ini.

```cpp
class DateTime
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan hasil penjumlahan rentang waktu yang ditentukan dengan nilai tanggal dan waktu yang diwakili oleh objek saat ini. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan jumlah hari yang ditentukan. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan jumlah jam yang ditentukan. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan jumlah milidetik yang ditentukan. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan jumlah menit yang ditentukan. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan jumlah bulan yang ditentukan. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan jumlah detik yang ditentukan. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan jumlah nilai yang diwakili oleh objek saat ini dan jumlah interval 100-nanodetik yang ditentukan. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Mengembalikan instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang sama dengan yang diwakili oleh objek saat ini dengan komponen tahun ditambah jumlah yang ditentukan. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Membandingkan dua nilai yang diwakili oleh instance kelas [DateTime](./) yang ditentukan dan mengembalikan nilai yang menunjukkan posisi relatif nilai pada garis waktu. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Membandingkan dua nilai tanggal dan waktu yang diwakili oleh objek saat ini dan instance [DateTime](./) yang ditentukan, kemudian mengembalikan nilai yang menunjukkan posisi relatif nilai pada garis waktu. |
| constexpr [DateTime](./datetime/)() | Membuat sebuah instance yang mewakili nilai tanggal dan waktu terkecil yang mungkin sama dengan MinValue. |
| [DateTime](./datetime/)(int, int, int) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, dan hari tertentu. |
| [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, dan hari tertentu dalam kalender yang ditentukan. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, dan detik tertentu. |
| [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, dan detik tertentu. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, dan detik tertentu dalam kalender yang ditentukan. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, detik, dan milidetik tertentu. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, detik, dan milidetik tertentu dalam kalender yang ditentukan. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai sejumlah tick. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Membuat sebuah instance yang mewakili nilai tanggal dan waktu yang ditentukan sebagai sejumlah tick. UNTUK PENGGUNAAN INTERNAL. |
| [DateTime](./datetime/)(const [DateTime](./)\&) | Membuat instance dengan copy-constructor. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Mengembalikan jumlah hari dalam bulan yang ditentukan pada tahun yang ditentukan. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Menentukan apakah instance [DateTime](./) yang ditentukan mewakili nilai tanggal dan waktu yang sama. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Menentukan apakah instance [DateTime](./) yang ditentukan mewakili nilai tanggal dan waktu yang sama dengan objek saat ini. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Mendeserialisasi nilai tanggal dan waktu dari integer 64-bit tak bertanda yang ditentukan dan mengatur instance baru kelas [DateTime](./) ke nilai tersebut. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Mengubah waktu File yang ditentukan menjadi instance kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang sama sebagai waktu lokal. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Mengubah waktu File yang ditentukan menjadi instance kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang sama sebagai waktu UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Mengembalikan instance kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang setara dengan OLE Automation Date yang ditentukan. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Mengubah nilai waktu Unix yang ditentukan menjadi instance kelas [DateTime](./). UNTUK PENGGUNAAN INTERNAL. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Mengembalikan instance baru kelas [DateTime](./) yang mewakili bagian tanggal dari tanggal dan waktu yang diwakili oleh objek saat ini dengan setiap komponen bagian waktu diset ke 0. |
| int [get_Day](./get_day/)() const | Mengembalikan nomor urut hari dalam bulan yang diwakili oleh objek saat ini. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Mengembalikan nilai yang mewakili hari dalam minggu yang diwakili oleh objek saat ini. |
| int [get_DayOfYear](./get_dayofyear/)() const | Mengembalikan nomor urut hari dalam tahun yang diwakili oleh objek saat ini. |
| constexpr int [get_Hour](./get_hour/)() const | Mengembalikan komponen jam dari nilai tanggal dan waktu yang diwakili oleh objek saat ini. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Mengembalikan nilai yang menunjukkan apakah tanggal dan waktu yang diwakili oleh objek saat ini adalah lokal, UTC, atau tidak keduanya. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Mengembalikan komponen milidetik dari nilai tanggal dan waktu yang diwakili oleh objek saat ini. |
| constexpr int [get_Minute](./get_minute/)() const | Mengembalikan komponen menit dari nilai tanggal dan waktu yang diwakili oleh objek saat ini. |
| int [get_Month](./get_month/)() const | Mengembalikan nomor urut bulan dalam tahun yang diwakili oleh objek saat ini. |
| static [DateTime](./) [get_Now](./get_now/)() | Mengembalikan instance kelas [DateTime](./) yang mewakili waktu saat ini sebagai waktu lokal. |
| constexpr int [get_Second](./get_second/)() const | Mengembalikan komponen detik dari nilai tanggal dan waktu yang diwakili oleh objek saat ini. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Mengembalikan jumlah interval 100-nanodetik yang telah berlalu sejak 0:00:00 UTC, 1 Januari 0001, dalam kalender Gregorian hingga tanggal dan waktu yang diwakili oleh objek saat ini. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Mengembalikan nilai yang mewakili interval waktu dari awal hari yang diwakili oleh objek saat ini hingga nilai tanggal dan waktu yang diwakili oleh objek saat ini. |
| static [DateTime](./) [get_Today](./get_today/)() | Mengembalikan instance kelas [DateTime](./) yang mewakili tanggal saat ini dengan setiap komponen bagian waktu dari nilai yang diwakili oleh objek diset ke 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Mengembalikan instance kelas [DateTime](./) yang mewakili waktu saat ini sebagai UTC. |
| int [get_Year](./get_year/)() const | Mengembalikan tahun yang diwakili oleh objek saat ini. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Mendapatkan bagian-bagian tanggal. UNTUK PENGGUNAAN INTERNAL. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Mengembalikan array string dimana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan salah satu penentu format tanggal dan waktu standar. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Mengembalikan array string dimana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan penentu format tanggal dan waktu standar yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengembalikan array string dimana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan salah satu penentu format tanggal dan waktu standar dan penyedia format yang ditentukan. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengembalikan array string dimana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan penentu format tanggal dan waktu standar yang ditentukan dan penyedia format. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Menentukan apakah nilai tanggal dan waktu yang diwakili oleh objek saat ini berada dalam rentang waktu daylight saving time untuk zona waktu saat ini. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Menentukan apakah tahun yang ditentukan merupakan tahun kabisat. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Menentukan apakah objek saat ini dan objek [DateTime](./) yang ditentukan mewakili nilai tanggal dan waktu yang berbeda. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Mengembalikan instance baru kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan hasil penjumlahan nilai yang diwakili oleh objek saat ini dengan rentang waktu yang ditentukan. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Menetapkan objek saat ini ke nilai tanggal dan waktu yang merupakan hasil penjumlahan nilai yang diwakili oleh objek saat ini dengan rentang waktu yang ditentukan. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Mengembalikan instance baru kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang diwakili oleh objek saat ini. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Mengembalikan instance kelas [TimeSpan](../timespan/) yang mewakili interval waktu antara nilai tanggal dan waktu yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Menetapkan objek saat ini ke nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai tanggal dan waktu yang diwakili oleh objek saat ini. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Menentukan apakah objek saat ini mewakili nilai tanggal dan waktu yang lebih awal daripada nilai yang diwakili oleh objek [DateTime](./) yang ditentukan. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Menentukan apakah objek saat ini mewakili nilai tanggal dan waktu yang lebih awal atau sama dengan nilai yang diwakili oleh objek [DateTime](./) yang ditentukan. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Menetapkan nilai yang diwakili oleh instance [DateTime](./) yang ditentukan ke objek saat ini. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Menentukan apakah objek saat ini dan objek [DateTime](./) yang ditentukan mewakili nilai tanggal dan waktu yang sama. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Menentukan apakah objek saat ini mewakili nilai tanggal dan waktu yang lebih lambat daripada nilai yang diwakili oleh objek [DateTime](./) yang ditentukan. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Menentukan apakah objek saat ini mewakili nilai tanggal dan waktu yang lebih lambat atau sama dengan nilai yang diwakili oleh objek [DateTime](./) yang ditentukan. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Mengonversi representasi string tanggal dan waktu yang ditentukan menjadi objek [DateTime](./) yang setara. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Mengonversi representasi string tanggal dan waktu yang ditentukan menjadi objek [DateTime](./) yang setara dengan menggunakan informasi format spesifik budaya. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Mengonversi representasi string tanggal dan waktu yang ditentukan menjadi objek [DateTime](./) yang setara dengan menggunakan format yang ditentukan dan informasi format spesifik budaya. Format representasi string harus persis cocok dengan format yang ditentukan. Melemparkan pengecualian jika konversi gagal. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Mengonversi representasi string tanggal dan waktu yang ditentukan menjadi objek [DateTime](./) yang setara dengan menggunakan format yang ditentukan, informasi format spesifik budaya, dan gaya. Format representasi string harus persis cocok dengan satu atau lebih format yang ditentukan. Melemparkan pengecualian jika konversi gagal. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Membuat objek [DateTime](./) baru yang mewakili jumlah tick yang sama dengan objek [DateTime](./) yang ditentukan dan mewakili waktu lokal, waktu UTC, atau tidak keduanya sebagaimana ditentukan oleh argumen **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Mengembalikan sebuah instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang diwakili oleh objek saat ini. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Mengembalikan sebuah instance dari kelas [TimeSpan](../timespan/) yang mewakili interval waktu antara nilai tanggal dan waktu yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| **int64_t** [ToBinary](./tobinary/)() const | Menyerialisasi objek saat ini. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Mengembalikan nilai yang mewakili nilai tanggal dan waktu yang diwakili oleh objek saat ini sebagai File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Mengonversi nilai tanggal dan waktu yang diwakili oleh objek saat ini ke File time UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Mengembalikan sebuah instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang diwakili oleh objek saat ini sebagai waktu lokal. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Mengembalikan string yang berisi representasi string tanggal panjang dari objek saat ini. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Mengembalikan string yang berisi representasi string waktu panjang dari objek saat ini. |
| **double** [ToOADate](./tooadate/)() const | Mengembalikan nilai tanggal dan waktu yang diwakili oleh objek saat ini sebagai OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Mengembalikan string yang berisi representasi string tanggal pendek dari objek saat ini. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Mengembalikan string yang berisi representasi string waktu pendek dari objek saat ini. |
| [String](../string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari nilai tanggal dan waktu yang diwakili oleh objek saat ini menggunakan konvensi format yang ditetapkan oleh budaya saat ini. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Mengembalikan representasi string dari nilai tanggal dan waktu yang diwakili oleh objek saat ini menggunakan format yang ditentukan dan konvensi format yang ditetapkan oleh budaya saat ini. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengembalikan representasi string dari nilai tanggal dan waktu yang diwakili oleh objek saat ini menggunakan informasi format yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengembalikan representasi string dari nilai tanggal dan waktu yang diwakili oleh objek saat ini menggunakan informasi format yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Mengembalikan sebuah instance baru dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu yang diwakili oleh objek saat ini sebagai UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Mengembalikan nilai yang mewakili nilai tanggal dan waktu yang diwakili oleh objek saat ini sebagai Unix time. UNTUK PENGGUNAAN INTERNAL. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Mengonversi representasi string tanggal dan waktu yang ditentukan menjadi objek [DateTime](./) yang setara. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Mengonversi representasi string tanggal dan waktu yang ditentukan menjadi objek [DateTime](./) yang setara dengan menggunakan informasi format spesifik budaya dan gaya yang ditentukan. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Mengonversi representasi string tanggal dan waktu yang ditentukan menjadi objek [DateTime](./) yang setara dengan menggunakan format yang ditentukan, informasi format spesifik budaya, dan gaya. Format representasi string harus persis cocok dengan format yang ditentukan. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Mengonversi representasi string tanggal dan waktu yang ditentukan menjadi objek [DateTime](./) yang setara dengan menggunakan format yang ditentukan, informasi format spesifik budaya, dan gaya. Format representasi string harus persis cocok dengan satu atau lebih format yang ditentukan. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Mengembalikan sebuah objek [TypeInfo](../typeinfo/) yang berisi informasi tentang kelas ini. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Jumlah 100-nanodetik dalam interval waktu antara nilai [DateTime](./) minimal yang mungkin dan maksimal yang mungkin. |
| static [MaxValue](./maxvalue/) | Sebuah instance dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu maksimal yang mungkin. |
| static constexpr [MinTicks](./minticks/) | Jumlah minimal tick yang dapat direpresentasikan oleh sebuah instance dari kelas [DateTime](./). |
| static [MinValue](./minvalue/) | Sebuah instance dari kelas [DateTime](./) yang mewakili nilai tanggal dan waktu minimal yang mungkin. |
| static constexpr [TicksPerDay](./ticksperday/) | Jumlah tick dalam satu hari. |
| static constexpr [TicksPerHour](./ticksperhour/) | Jumlah tick dalam satu jam. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Jumlah tick dalam satu mikrodetik. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Jumlah tick dalam satu milidetik. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Jumlah tick dalam satu menit. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Jumlah tick dalam satu detik. |
| static [UnixEpoch](./unixepoch/) | Sebuah instance dari kelas [DateTime](./) yang mewakili permulaan epoch Unix (1970.01.01 00:00:00). |
## Keterangan



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Buat instance kelas 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Cetak instance dalam berbagai format.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)