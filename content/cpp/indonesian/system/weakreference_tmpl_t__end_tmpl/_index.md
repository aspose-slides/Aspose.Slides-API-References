---
title: WeakReference< T >
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili referensi lemah, yang merujuk ke sebuah objek sekaligus masih memungkinkan objek tersebut dihapus.
type: docs
weight: 1509
url: /id/system/weakreference_tmpl_t__end_tmpl/
---
## WeakReference< T > kelas


Mewakili referensi lemah, yang merujuk ke sebuah objek sekaligus masih memungkinkan objek tersebut dihapus.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Type of a referenced object. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Mendapatkan tipe aktual dari objek. Analog panggilan C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator C# 'is'. |
| void [Lock](../object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengizinkan konstruktor salin subclass. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Memeriksa apakah objek yang dirujuk tidak null. |
| **bool** [operator!=](./operator_not_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Membandingkan objek yang dirujuk dengan instance lain kelas WeakReference. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengizinkan konstruktor salin subclass. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Memeriksa apakah objek yang dirujuk null. |
| **bool** [operator==](./operator_equal_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Membandingkan objek yang dirujuk dengan instance lain kelas WeakReference. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi jumlah referensi bersama dengan nilai yang ditentukan. |
| void [reset](./reset/)() |  |
| void [SetTarget](./settarget/)(const [SmartPtr](../smartptr/)\<T\>\&) | Mengatur objek (target) yang dirujuk oleh objek WeakReference saat ini. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi pointer lemah (bukan bersama). Memungkinkan berpindah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog dari metode C# [Object.ToString()](../object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| **bool** [TryGetTarget](./trygettarget/)(const [SmartPtr](../smartptr/)\<T\>\&) const | Mendapatkan objek (target) yang dirujuk oleh objek WeakReference saat ini. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
|  [WeakReference](./weakreference/)() | Konstruktor default. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor dari nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&) | Menginisialisasi instance baru dari kelas WeakReference, yang merujuk ke objek yang ditentukan. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&, **bool**) | Menginisialisasi instance baru dari kelas WeakReference, yang merujuk ke objek yang ditentukan. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../object/)
* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)