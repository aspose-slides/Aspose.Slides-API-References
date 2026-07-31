---
title: Details_AggregateException
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sebuah pengecualian yang berisi beberapa pengecualian internal.
type: docs
weight: 300
url: /id/system/details_aggregateexception/
---
## Details_AggregateException kelas

Represents an exception that contains multiple inner exceptions.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## Metode

| Method | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | Memperingkas exception agregat dengan membuka semua AggregateExceptions bersarang menjadi daftar satu tingkat. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Mengembalikan kamus dengan data exception khusus. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Mengembalikan nilai integer 32-bit yang merupakan kode HRESULT yang terkait dengan exception reprsented oleh objek saat ini. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Mengembalikan referensi ke objek yang merepresentasikan exception internal. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | Mendapatkan jumlah exception internal yang terdapat dalam exception agregat ini. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | Mendapatkan koleksi hanya-baca dari exception internal. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | Mengembalikan array internal dari exception internal. |
| [String](../string/) [get_Message](./get_message/)() const override | Menimpa pesan dasar untuk menyertakan informasi agregat dari semua exception internal. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Mengembalikan string yang berisi jejak stack. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | Mengembalikan exception penyebab akar dengan membuka secara rekursif exception internal. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../object/gethashcode/). Mengaktifkan hashing pada objek khusus. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Mendapatkan tipe aktual dari objek. Analog panggilan C# [System.Object.GetType()](../object/gettype/). |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | Memanggil fungsi handler pada setiap exception internal dan melempar kembali exception yang tidak ditangani. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek merepresentasikan sebuah instansi tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Mengatur HRESULT, nilai numerik yang dikodekan yang diberikan ke exception tertentu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengganti pointer di dalam kontainer ke mode lemah. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Mengembalikan representasi string dari exception, termasuk semua exception internal. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Mengimplementasikan pembebasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Mengimplementasikan metode [what()](../details_exception/what/) yang dipanggil oleh kelas [ExceptionWrapper](../exceptionwrapper/). Meskipun fakta bahwa kelas ini tidak diwarisi dari std::exception, kelas turunan dapat menggunakan anggota protected/private untuk mengimplementasikan logika mereka. Memindahkan implementasi metode ini ke [ExceptionWrapper](../exceptionwrapper/) dapat merusak logika tersebut. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Keterangan

Kelas ini biasanya digunakan untuk mengelompokkan beberapa exception yang terjadi secara bersamaan, seperti dalam pemrosesan paralel atau skenario eksekusi tugas asinkron. Ini memungkinkan pengguna untuk memeriksa, memperkecil, atau menangani secara selektif exception yang terkandung. 

## Lihat Juga

* Kelas [Details_Exception](../details_exception/)
* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)