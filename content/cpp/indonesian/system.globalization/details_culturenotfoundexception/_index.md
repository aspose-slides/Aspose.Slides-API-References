---
title: Details_CultureNotFoundException
second_title: Aspose.Slides untuk Referensi API C++
description: "CultureNotFoundException dilemparkan ketika upaya dilakukan untuk membangun budaya yang tidak tersedia. Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas CultureNotFoundException sebagai gantinya. Jangan pernah membungkus instance kelas CultureNotFoundException ke dalam System::SmartPtr."
type: docs
weight: 92
url: /id/system.globalization/details_culturenotfoundexception/
---
## Details_CultureNotFoundException kelas


CultureNotFoundException dilemparkan ketika upaya dilakukan untuk membangun budaya yang tidak tersedia. Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas CultureNotFoundException sebagai gantinya. Jangan pernah membungkus instance kelas CultureNotFoundException ke dalam [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_CultureNotFoundException : public System::Details_ArgumentException
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Mengembalikan kamus dengan data pengecualian khusus. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Mengembalikan nilai integer 32-bit yang merupakan kode HRESULT terkait dengan pengecualian yang direpresentasikan oleh objek saat ini. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Mengembalikan referensi ke objek yang mewakili pengecualian dalam. |
| virtual [Nullable](../../system/nullable/)\<int\> [get_InvalidCultureId](./get_invalidcultureid/)() const |  |
| virtual [String](../../system/string/) [get_InvalidCultureName](./get_invalidculturename/)() const |  |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Mengembalikan string yang berisi deskripsi kesalahan. |
| [String](../../system/string/) [get_ParamName](../../system/details_argumentexception/get_paramname/)() |  |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Mengembalikan string yang berisi jejak tumpukan. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Mengembalikan salinan objek Exception yang mewakili pengecualian terdalam. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_argumentexception/gettype/)() const override | Mendapatkan tipe aktual objek. Analogi pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_argumentexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Mengatur HRESULT, nilai numerik terkode yang ditetapkan ke pengecualian spesifik. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan bersama). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Mengembalikan representasi string dari objek saat ini. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_argumentexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Mengimplementasikan metode [what()](../../system/details_exception/what/) yang dipanggil oleh kelas [ExceptionWrapper](../../system/exceptionwrapper/). Meskipun fakta bahwa kelas ini tidak diturunkan dari std::exception, kelas turunan dapat menggunakan anggota protected/private untuk mengimplementasikan logikanya. Memindahkan implementasi metode ini ke [ExceptionWrapper](../../system/exceptionwrapper/) dapat merusak logika tersebut. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Details_ArgumentException](../../system/details_argumentexception/)
* Ruang nama [System::Globalization](../)
* Pustaka [Aspose.Slides](../../)