---
title: KoreanLunisolarCalendar
second_title: Referensi API Aspose.Slides untuk C++
description: "Kalender lunisolar Korea. Tidak diimplementasikan. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen."
type: docs
weight: 235
url: /id/system.globalization/koreanlunisolarcalendar/
---
## KoreanLunisolarCalendar kelas

Kalendar lunisolar Korea. Tidak diimplementasikan. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan error runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen.

```cpp
class KoreanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Metode

| Method | Description |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Membuat salinan objek saat ini dan mengembalikan pointer bersama ke objek tersebut. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | Informasi RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Mendapatkan indeks era saat ini. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Mendapatkan nilai era saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Mendapatkan daftar era yang ada dalam kalender. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Memeriksa apakah kalender hanya baca. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Titik waktu maksimal yang didukung oleh kalender. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Titik waktu minimal yang didukung oleh kalender. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Mendapatkan tahun terakhir yang dapat direpresentasikan dengan 2 digit. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Mendapatkan batang selestial. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Mendapatkan hari dalam bulan untuk titik waktu yang ditentukan. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Mendapatkan hari dalam minggu untuk titik waktu yang ditentukan. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Mendapatkan hari dalam tahun untuk titik waktu yang ditentukan. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Mendapatkan jumlah hari dalam bulan tertentu. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Mendapatkan jumlah hari dalam bulan tertentu. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Mendapatkan jumlah hari dalam tahun tertentu. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Mendapatkan jumlah hari dalam tahun tertentu. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Mendapatkan era untuk titik waktu yang ditentukan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hash objek khusus. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Mendapatkan jam untuk titik waktu yang ditentukan. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Mendapatkan bulan kabisat untuk tahun yang ditentukan. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Informasi RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Informasi RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Mendapatkan milidetik untuk titik waktu yang ditentukan. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Mendapatkan menit untuk titik waktu yang ditentukan. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Mendapatkan bulan untuk titik waktu yang ditentukan. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Mendapatkan jumlah bulan dalam tahun yang ditentukan. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Mendapatkan jumlah bulan dalam tahun yang ditentukan. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Mendapatkan detik untuk titik waktu yang ditentukan. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Mendapatkan tahun dalam siklus seksagenari. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | Mendapatkan cabang terestrial. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Mendapatkan minggu dalam tahun untuk titik waktu yang ditentukan. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Mendapatkan tahun untuk titik waktu yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Periksa apakah objek mewakili instansi tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Memeriksa apakah hari kabisat. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Memeriksa apakah hari kabisat. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Memeriksa apakah hari kabisat. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Memeriksa apakah bulan kabisat. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Memeriksa apakah bulan kabisat. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Memeriksa apakah tahun kabisat. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Memeriksa apakah tahun kabisat. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Memeriksa apakah tahun kabisat. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Memeriksa nilai tahun, bulan, hari, dan era. |
|  [KoreanLunisolarCalendar](./koreanlunisolarcalendar/)() | Konstruktor. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin untuk subclass. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin untuk subclass. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Mendapatkan versi hanya baca dari kalender. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Mengatur tahun terakhir yang dapat direpresentasikan dengan 2 digit. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Membuat objek [DateTime](../../system/datetime/) dari komponen. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Membuat objek [DateTime](../../system/datetime/) dari komponen. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Mengonversi tahun ke tahun 4 digit menggunakan properti TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Field | Description |
| --- | --- |
| static constexpr [GregorianEra](./gregorianera/) | Era Gregorian saat ini. |

## Lihat Juga

* Kelas [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Ruang Nama [System::Globalization](../)
* Perpustakaan [Aspose.Slides](../../)