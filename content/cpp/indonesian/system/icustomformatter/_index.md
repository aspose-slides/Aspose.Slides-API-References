---
title: ICustomFormatter
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan sebuah metode yang melakukan pemformatan khusus pada representasi string dari nilai yang direpresentasikan oleh objek yang ditentukan. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer tersebut untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 950
url: /id/system/icustomformatter/
---
## ICustomFormatter kelas

Mendefinisikan metode yang melakukan pemformatan khusus dari representasi string nilai yang direpresentasikan oleh objek yang ditentukan. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../makeobject/). Jangan pernah membuat contoh (instance) dari tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class ICustomFormatter : public virtual System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [System::String](../string/) [Format](./format/)([System::String](../string/), [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Mengembalikan representasi string dari nilai yang direpresentasikan oleh objek saat ini menggunakan format yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari panggilan C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor penyalin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruktor pada subclass. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog dari metode C# [Object.ToString()](../object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Mengimplementasikan konstruk tipe C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../object/)
* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)