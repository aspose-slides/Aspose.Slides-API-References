---
title: Details_NotImplementedException
second_title: Referensi API Aspose.Slides untuk C++
description: "NotImplementedException dilempar ketika sebuah metode yang belum diimplementasikan dan berfungsi sebagai stub. Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas NotImplementedException sebagai gantinya. Jangan pernah membungkus instance kelas NotImplementedException ke dalam System::SmartPtr."
type: docs
weight: 573
url: /id/system/details_notimplementedexception/
---
## Details_NotImplementedException kelas


NotImplementedException dilempar ketika sebuah metode yang belum diimplementasikan dan berfungsi sebagai stub. Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas NotImplementedException sebagai gantinya. Jangan pernah membungkus instance kelas NotImplementedException ke dalam [System::SmartPtr](../smartptr/).

```cpp
class Details_NotImplementedException : public System::Details_SystemException
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Mengembalikan kamus dengan data pengecualian khusus. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Mengembalikan nilai integer 32-bit yang merupakan kode HRESULT terkait dengan pengecualian yang diwakili oleh objek saat ini. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Mengembalikan referensi ke objek yang mewakili pengecualian internal. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Mengembalikan string yang berisi deskripsi kesalahan. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Mengembalikan string yang berisi jejak tumpukan. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Mengembalikan salinan objek Exception yang mewakili pengecualian terdalam. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../object/gethashcode/). Mengaktifkan hashing objek khusus. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor penyalin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Mengatur HRESULT, nilai numerik terkode yang diberikan kepada pengecualian tertentu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Mengembalikan representasi string dari objek saat ini. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Menerapkan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Menerapkan metode [what()](../details_exception/what/) yang dipanggil oleh kelas [ExceptionWrapper](../exceptionwrapper/). Meskipun kelas ini tidak diturunkan dari std::exception, kelas turunan dapat menggunakan anggota protected/private untuk mengimplementasikan logika mereka. Memindahkan implementasi metode ini ke [ExceptionWrapper](../exceptionwrapper/) dapat merusak logika tersebut. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Details_SystemException](../details_systemexception/)
* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)