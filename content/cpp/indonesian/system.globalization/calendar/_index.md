---
title: Calendar
second_title: Referensi API Aspose.Slides untuk C++
description: "Calendar yang menentukan bagaimana tanggal ditangani, dihitung, diformat, dll. Operasi setter hanya diaktifkan pada objek yang tidak bersifat read-only. Objek dari kelas ini harus dialokasikan hanya menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 1
url: /id/system.globalization/calendar/
---
## Calendar kelas

[Calendar](./) yang mendefinisikan bagaimana tanggal ditangani, dihitung, diformat, dll. Operasi setter hanya diaktifkan pada objek yang tidak bersifat read-only. Objek dari kelas ini harus dialokasikan hanya menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class Calendar : public System::ICloneable
```

## Metode

| Method | Deskripsi |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | Menambahkan hari ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | Menambahkan jam ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Menambahkan milidetik ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | Menambahkan menit ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | Menambahkan bulan ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | Menambahkan detik ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | Menambahkan minggu ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | Menambahkan tahun ke titik waktu. |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | Informasi RTTI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Membuat salinan objek saat ini dan mengembalikan shared pointer kepadanya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | Mendapatkan tipe algoritma. |
| int [get_CurrentEra](./get_currentera/)() const | Mendapatkan indeks era saat ini. |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | Mendapatkan nilai era saat ini. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | Mendapatkan daftar era yang ada dalam kalender. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | Mendapatkan identifier kalender. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Memeriksa apakah kalender bersifat read-only. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Titik waktu maksimal yang didukung oleh kalender. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Titik waktu minimal yang didukung oleh kalender. |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Mendapatkan tahun terakhir yang dapat direpresentasikan dengan 2 digit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | Mendapatkan hari dalam bulan untuk titik waktu yang ditentukan. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | Mendapatkan hari dalam minggu untuk titik waktu yang ditentukan. |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | Mendapatkan hari dalam tahun untuk titik waktu yang ditentukan. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Mendapatkan jumlah hari dalam bulan tertentu. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Mendapatkan jumlah hari dalam bulan tertentu. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Mendapatkan jumlah hari dalam tahun tertentu. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Mendapatkan jumlah hari dalam tahun tertentu. |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | Mendapatkan era untuk titik waktu yang ditentukan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | Mendapatkan jam untuk titik waktu yang ditentukan. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Mendapatkan bulan kabisat untuk tahun yang ditentukan. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Mendapatkan bulan kabisat untuk tahun yang ditentukan. |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | Mendapatkan milidetik untuk titik waktu yang ditentukan. |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | Mendapatkan menit untuk titik waktu yang ditentukan. |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | Mendapatkan bulan untuk titik waktu yang ditentukan. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Mendapatkan jumlah bulan dalam tahun yang ditentukan. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Mendapatkan jumlah bulan dalam tahun yang ditentukan. |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | Mendapatkan detik untuk titik waktu yang ditentukan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Mendapatkan minggu dalam tahun untuk titik waktu yang ditentukan. |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | Mendapatkan tahun untuk titik waktu yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Memeriksa apakah hari tersebut kabisat. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Memeriksa apakah hari tersebut kabisat. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Memeriksa apakah bulan tersebut kabisat. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Memeriksa apakah bulan tersebut kabisat. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Memeriksa apakah tahun tersebut kabisat. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Memeriksa apakah tahun tersebut kabisat. |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | Memeriksa nilai tahun, bulan, hari, dan era. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan lock() C#. Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | Mendapatkan versi read-only dari kalender. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek lewat referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek lewat referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi counter referensi bersama dengan nilai yang ditentukan. |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Mengatur tahun terakhir yang dapat direpresentasikan dengan 2 digit. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer di kontainer menjadi mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari counter referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah counter referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan counter referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Membuat objek [DateTime](../../system/datetime/) dari komponen. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Membuat objek [DateTime](../../system/datetime/) dari komponen. |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | Mengonversi tahun menjadi tahun 4 digit menggunakan properti TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan unlock() C#. Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah counter referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi counter referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [ICloneable](../../system/icloneable/)
* Ruang nama [System::Globalization](../)
* Library [Aspose.Slides](../../)