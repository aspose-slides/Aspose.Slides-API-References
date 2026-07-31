---
title: Object
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas dasar yang memungkinkan penggunaan metode yang tersedia untuk kelas System.Object dalam C#. Semua kelas non-trivial yang digunakan dengan lingkungan terjemahan harus mewarisinya.
type: docs
weight: 1132
url: /id/system/object/
---
## Object kelas

Kelas dasar yang memungkinkan penggunaan metode yang tersedia untuk kelas [System.Object](./) dalam C#. Semua kelas non-trivial yang digunakan dengan lingkungan terjemahan harus mewarisinya.

```cpp
class Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](./gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Mendapatkan tipe aktual dari objek. Analogi pemanggilan C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](./lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](./memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](./object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](./object/)([Object](./) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](./referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](./referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](./sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analogi metode C# [Object.ToString()](./tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Mengimplementasikan konstruktion C# typeof([System.Object](./)). |
| void [Unlock](./unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](./~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [ptr](./ptr/) | Alias untuk tipe smart pointer. |

## Keterangan

Selain metode yang tersedia dalam kelas C# [System.Object](./), ia juga mendukung beberapa konsep khusus untuk lingkungan kode terjemahan. Ini termasuk penghitung referensi yang digunakan oleh kelas smart pointer ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) dan layanan lain yang berhubungan dengan manajemen memori, debug, dll.

Setiap [Object](./) memiliki dua penghitung referensi: penghitung referensi bersama dan penghitung referensi lemah. Penghitung referensi lemah selalu disimpan dalam struktur data terpisah, bukan di dalam [Object](./) itu sendiri, yang memungkinkan weak pointer tetap hidup lebih lama daripada objek yang direferensikan. Penghitung referensi pintar disimpan baik di dalam objek itu sendiri atau di struktur terpisah yang sama, bergantung pada keadaan makro ENABLE_EXTERNAL_REFCOUNT. Secara default, itu diaktifkan pada build debug dan dinonaktifkan pada build release. Jika penghitung smart pointer disimpan di dalam objek, struktur data terpisah dibuat hanya jika ada weak pointer ke objek. Jika tidak, struktur tersebut dibuat bersamaan dengan objek.

Semua smart pointer menggunakan kedua penghitung referensi ini dan berkontribusi pada satu grup kepemilikan yang sama.

Jika subclass [Object](./) dibuat di stack, tidak boleh dibuat smart pointer ke itu, jika tidak akan terjadi masalah penghapusan stack.

Tipe ini dapat dialokasikan baik di stack sebagai tipe nilai atau di heap menggunakan fungsi [System::MakeObject()](../makeobject/). Setelah objek dialokasikan, jangan pernah mencampur kedua kasus penggunaan ini: memiliki pointer [SmartPtr](../smartptr/) ke objek yang dialokasikan di stack dilarang keras.

## Lihat Juga

* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)