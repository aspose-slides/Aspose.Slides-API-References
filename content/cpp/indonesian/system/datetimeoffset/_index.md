---
title: DateTimeOffset
second_title: Referensi API Aspose.Slides untuk C++
description: "Berisi tanggal dan waktu hari relatif terhadap Coordinated Universal Time. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk mengirimnya ke fungsi sebagai argumen."
type: docs
weight: 235
url: /id/system/datetimeoffset/
---
## DateTimeOffset kelas

Berisi tanggal dan waktu hari relatif terhadap Coordinated Universal Time. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../smartptr/) dan gunakan pointer ini untuk mengirimkannya ke fungsi sebagai argumen.

```cpp
class DateTimeOffset
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Menambahkan interval waktu yang ditentukan ke objek [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Menambahkan sejumlah hari yang ditentukan ke objek [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Menambahkan sejumlah jam yang ditentukan ke objek [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Menambahkan sejumlah milidetik yang ditentukan ke objek [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Menambahkan sejumlah menit yang ditentukan ke objek [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Menambahkan sejumlah bulan yang ditentukan ke objek [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Menambahkan sejumlah detik yang ditentukan ke objek [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Menambahkan sejumlah tick yang ditentukan ke objek [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Menambahkan sejumlah tahun yang ditentukan ke objek [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Membandingkan dua objek [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Membandingkan dua objek [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Membandingkan dua objek [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Konstruktor default. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Konstruktor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Memeriksa apakah dua objek [DateTimeOffset](./) mewakili titik waktu yang sama. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Memeriksa apakah dua objek [DateTimeOffset](./) mewakili titik waktu yang sama. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Memeriksa apakah dua objek [DateTimeOffset](./) mewakili titik waktu yang sama. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Memeriksa apakah dua objek [DateTimeOffset](./) mewakili titik waktu yang sama dan memiliki offset yang sama. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Memeriksa apakah dua objek [DateTimeOffset](./) mewakili titik waktu yang sama dan memiliki offset yang sama. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) waktu file menjadi tanggal dan waktu dengan offset waktu lokal. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time menjadi objek [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time menjadi objek [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Mendapatkan komponen tanggal dari objek saat ini. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Mendapatkan nilai [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Mendapatkan hari dalam bulan dari objek saat ini. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Mendapatkan hari dalam minggu dari objek saat ini. |
| int [get_DayOfYear](./get_dayofyear/)() const | Mendapatkan hari dalam tahun dari objek saat ini. |
| int [get_Hour](./get_hour/)() const | Mendapatkan komponen jam dari objek saat ini. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Mendapatkan nilai [DateTime](../datetime/) yang mewakili tanggal dan waktu lokal. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Mendapatkan komponen milidetik dari objek saat ini. |
| int [get_Minute](./get_minute/)() const | Mendapatkan komponen menit dari objek saat ini. |
| int [get_Month](./get_month/)() const | Mendapatkan komponen bulan dari objek saat ini. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Mendapatkan [DateTimeOffset](./) yang tanggal dan waktunya diatur ke waktu lokal saat ini dan offsetnya diatur ke offset waktu lokal. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Mendapatkan offset dari UTC. |
| constexpr int [get_Second](./get_second/)() const | Mendapatkan komponen detik dari objek saat ini. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Mendapatkan jumlah tick dari objek saat ini. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Mendapatkan waktu dalam hari dari objek saat ini. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Mendapatkan nilai [DateTime](../datetime/) yang mewakili tanggal dan waktu UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Mendapatkan [DateTimeOffset](./) yang tanggal dan waktunya diatur ke waktu UTC saat ini dan offsetnya [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Mendapatkan jumlah tick dari objek saat ini dalam waktu UTC. |
| int [get_Year](./get_year/)() const | Mendapatkan komponen tahun dari objek saat ini. |
| int [GetHashCode](./gethashcode/)() const | Mendapatkan kode hash untuk objek [DateTimeOffset](./) saat ini. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Menentukan apakah objek saat ini dan objek [DateTimeOffset](./) yang ditentukan mewakili nilai tanggal dan waktu yang berbeda. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Mengembalikan instance baru dari kelas [DateTimeOffset](./) yang mewakili nilai tanggal dan waktu yang merupakan jumlah dari nilai yang diwakili oleh objek saat ini dan rentang waktu yang ditentukan. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Mengembalikan instance baru dari kelas [DateTimeOffset](./) yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang diwakili oleh objek saat ini. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Mengembalikan sebuah instance dari kelas [TimeSpan](../timespan/) yang mewakili interval waktu antara nilai tanggal dan waktu yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Menentukan apakah objek saat ini mewakili nilai tanggal dan waktu yang lebih awal daripada nilai yang diwakili oleh objek [DateTimeOffset](./) yang ditentukan. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Menentukan apakah objek saat ini mewakili nilai tanggal dan waktu yang lebih awal atau sama dengan nilai yang diwakili oleh objek [DateTimeOffset](./) yang ditentukan. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Menentukan apakah objek saat ini dan objek [DateTimeOffset](./) yang ditentukan mewakili nilai tanggal dan waktu yang sama. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Menentukan apakah objek saat ini mewakili nilai tanggal dan waktu yang lebih lambat daripada nilai yang diwakili oleh objek [DateTimeOffset](./) yang ditentukan. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Menentukan apakah objek saat ini mewakili nilai tanggal dan waktu yang lebih lambat atau sama dengan nilai yang diwakili oleh objek [DateTimeOffset](./) yang ditentukan. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Mengubah string yang ditentukan menjadi setara [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Mengubah string yang ditentukan menjadi objek [DateTimeOffset](./) menggunakan penyedia format dan gaya format yang ditentukan. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Mengubah string yang ditentukan menjadi objek [DateTimeOffset](./) menggunakan format, penyedia format, dan gaya format yang ditentukan. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Mengubah string yang ditentukan menjadi objek [DateTimeOffset](./) menggunakan format-format, penyedia format, dan gaya format yang ditentukan. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Mengurangkan interval waktu yang ditentukan dari objek saat ini. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Mengurangkan nilai [DateTimeOffset](./) yang ditentukan dari objek saat ini. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Mengubah objek saat ini menjadi waktu file [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Mengubah objek saat ini menjadi sebuah objek yang mewakili waktu lokal. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Mengganti offset objek saat ini dengan offset yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengubah objek saat ini menjadi string menggunakan format dan penyedia format yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mengubah objek saat ini menjadi string menggunakan penyedia format yang ditentukan. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Mengubah objek saat ini menjadi string menggunakan format yang ditentukan. |
| [String](../string/) [ToString](./tostring/)() const | Mengubah objek saat ini menjadi string. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Mengubah objek saat ini menjadi sebuah objek yang mewakili waktu UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Mendapatkan milidetik yang telah berlalu sejak awal epoch Unix. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Mendapatkan detik yang telah berlalu sejak awal epoch Unix. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Mencoba mengubah string yang ditentukan menjadi objek [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Mencoba mengubah string yang ditentukan menjadi objek [DateTimeOffset](./) menggunakan penyedia format dan gaya format yang ditentukan. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Mencoba mengubah string yang ditentukan menjadi objek [DateTimeOffset](./) menggunakan format-format, penyedia format, dan gaya format yang ditentukan. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Mencoba mengubah string yang ditentukan menjadi objek [DateTimeOffset](./) menggunakan format, penyedia format, dan gaya format yang ditentukan. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Mengembalikan objek [TypeInfo](../typeinfo/) yang mewakili struktur [TimeSpan](../timespan/). |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Mendapatkan offset maksimum dalam tick. |
| static [MaxValue](./maxvalue/) | Mendapatkan nilai [DateTimeOffset](./) terbesar. |
| static constexpr [MinOffset](./minoffset/) | Mendapatkan offset minimum dalam tick. |
| static [MinValue](./minvalue/) | Mendapatkan nilai [DateTimeOffset](./) paling awal. |
| static [UnixEpoch](./unixepoch/) | Mendapatkan awal epoch Unix. |

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)