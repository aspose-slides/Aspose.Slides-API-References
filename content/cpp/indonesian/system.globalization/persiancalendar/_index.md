---
title: PersianCalendar
second_title: Referensi API Aspose.Slides untuk C++
description: "Kalender Persia. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena dapat menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam penunjuk System::SmartPtr dan gunakan penunjuk ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 261
url: /id/system.globalization/persiancalendar/
---
## PersianCalendar kelas

Kalender Persia. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam penunjuk [System::SmartPtr](../../system/smartptr/) dan gunakan penunjuk ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class PersianCalendar : public System::Globalization::Calendar
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Menambahkan hari ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Menambahkan jam ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Menambahkan milidetik ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Menambahkan menit ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Menambahkan bulan ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Menambahkan detik ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Menambahkan minggu ke titik waktu. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Menambahkan tahun ke titik waktu. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informasi RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Membuat salinan objek saat ini dan mengembalikan penunjuk bersama ke objek tersebut. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Mendapatkan tipe algoritma. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Mendapatkan indeks era saat ini. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Mendapatkan nilai era saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Mendapatkan daftar era yang ada dalam kalender. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Memeriksa apakah kalender hanya-baca. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Titik waktu maksimal yang didukung oleh kalender. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Titik waktu minimal yang didukung oleh kalender. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Mendapatkan tahun terakhir yang dapat direpresentasikan dengan dua digit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Mendapatkan hari dalam bulan untuk titik waktu yang ditentukan. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Mendapatkan hari dalam minggu untuk titik waktu yang ditentukan. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Mendapatkan hari dalam tahun untuk titik waktu yang ditentukan. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Mendapatkan jumlah hari dalam bulan tertentu. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Informasi RTTI. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Informasi RTTI. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Mendapatkan jumlah hari dalam tahun tertentu. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Mendapatkan jumlah hari dalam tahun tertentu. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Mendapatkan jumlah hari dalam tahun tertentu. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Mendapatkan era untuk titik waktu yang ditentukan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Mendapatkan jam untuk titik waktu yang ditentukan. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Mendapatkan bulan kabisat untuk tahun yang ditentukan. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Mendapatkan bulan kabisat untuk tahun yang ditentukan. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Mendapatkan bulan kabisat untuk tahun yang ditentukan. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Mendapatkan milidetik untuk titik waktu yang ditentukan. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Mendapatkan menit untuk titik waktu yang ditentukan. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Mendapatkan bulan untuk titik waktu yang ditentukan. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Mendapatkan jumlah bulan dalam tahun yang ditentukan. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Mendapatkan jumlah bulan dalam tahun yang ditentukan. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Mendapatkan jumlah bulan dalam tahun yang ditentukan. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Mendapatkan detik untuk titik waktu yang ditentukan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Mendapatkan minggu dalam tahun untuk titik waktu yang ditentukan. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Mendapatkan tahun untuk titik waktu yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Memeriksa apakah hari tersebut kabisat. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Memeriksa apakah hari tersebut kabisat. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Memeriksa apakah hari tersebut kabisat. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Memeriksa apakah bulan tersebut kabisat. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Memeriksa apakah bulan tersebut kabisat. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Memeriksa apakah bulan tersebut kabisat. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Memeriksa apakah tahun tersebut kabisat. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Memeriksa apakah tahun tersebut kabisat. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Memeriksa apakah tahun tersebut kabisat. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Memeriksa nilai tahun, bulan, hari, dan era. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan lock() C# untuk mengunci. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
|  [PersianCalendar](./persiancalendar/)() | Konstruktor. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Mendapatkan versi hanya-baca dari kalender. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Menurunkan penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Menetapkan tahun terakhir yang dapat direpresentasikan dengan dua digit. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi penunjuk lemah (bukan penunjuk bersama). Memungkinkan mengubah penunjuk dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Menurunkan dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Membangun objek [DateTime](../../system/datetime/) dari komponen. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Membangun objek [DateTime](../../system/datetime/) dari komponen. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Mengonversi tahun ke tahun 4-digit menggunakan properti TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan unlock() C# untuk membuka kunci. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Menurunkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [PersianEra](./persianera/) | Era Persia saat ini. |

## Lihat Juga

* Kelas [Calendar](../calendar/)
* Ruang nama [System::Globalization](../)
* Perpustakaan [Aspose.Slides](../../)