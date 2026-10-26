---
title: ExcelDataWorkbook
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili workbook yang menyediakan akses ke data Excel untuk penggunaan umum.
type: docs
weight: 14
url: /id/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook kelas


Mewakili sebuah workbook yang menyediakan akses ke data [Excel](../) untuk penggunaan umum.

```cpp
class ExcelDataWorkbook : public Aspose::Slides::Excel::IExcelDataWorkbook
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
|  [ExcelDataWorkbook](./exceldataworkbook/)([System::String](../../system/string/)) | Menginisialisasi instance baru menggunakan jalur file yang ditentukan. |
|  [ExcelDataWorkbook](./exceldataworkbook/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Menginisialisasi instance baru dari kelas menggunakan stream yang disediakan. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)(**int32_t**, **int32_t**, **int32_t**) override | Mengambil sel dari lembar kerja yang ditentukan menggunakan indeks dan koordinat selnya. |
| [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)([System::String](../../system/string/), **int32_t**, **int32_t**) override | Mengambil sel dari lembar kerja yang ditentukan menggunakan namanya dan koordinat sel. |
| [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)(**int32_t**, [System::String](../../system/string/)) override | Mengambil sel dari lembar kerja yang ditentukan menggunakan indeks dan nama sel gaya Excel (misalnya "B2"). |
| [System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\> [GetCell](./getcell/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Mengambil sel dari lembar kerja yang ditentukan menggunakan nama sel gaya Excel (misalnya "B2"). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[IExcelDataCell](../iexceldatacell/)\>\>\> [GetCells](./getcells/)([System::String](../../system/string/), **bool**) override | Mengambil sekumpulan sel dari workbook yang cocok dengan formula yang ditentukan. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<**int32_t**, [System::String](../../system/string/)\>\> [GetChartsFromWorksheet](./getchartsfromworksheet/)([System::String](../../system/string/)) override | Mengambil kamus yang berisi indeks dan nama semua grafik di lembar kerja yang ditentukan dari workbook [Excel](../). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::String](../../system/string/)\>\> [GetWorksheetNames](./getworksheetnames/)() override | Mengambil nama semua lembar kerja yang terdapat dalam workbook [Excel](../). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan penggandaan tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan konstruktor salin untuk subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan konstruktor salin untuk subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-nth menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IExcelDataWorkbook](../iexceldataworkbook/)
* Ruang Nama [Aspose::Slides::Excel](../)
* Library [Aspose.Slides](../../)