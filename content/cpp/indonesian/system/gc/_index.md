---
title: GC
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili Garbage Collection yang diemulasi yang berperilaku lebih seperti stub yang pada dasarnya tidak melakukan apa apa. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah harus membuat instance darinya dengan cara apapun.
type: docs
weight: 872
url: /id/system/gc/
---
## GC kelas

Mewakili Garbage Collection yang diemulasi yang berperilaku lebih seperti stub yang pada dasarnya tidak melakukan apa-apa. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah harus membuat instance darinya dengan cara apapun.

```cpp
class GC : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk tujuan internal. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../object/gethashcode/). Memungkinkan hashing objek kustom. |
| static **int64_t** [GetTotalAllocatedBytes](./gettotalallocatedbytes/)(**bool**) | Mengembalikan total byte yang dialokasikan. |
| static **int64_t** [GetTotalMemory](./gettotalmemory/)(**bool**) | Mengembalikan jumlah byte memori privat yang saat ini dialokasikan oleh proses saat ini. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog pemanggilan C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog metode C# [Object.ToString()](../object/tostring/). Memungkinkan mengkonversi objek kustom ke string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../object/)
* Ruang nama [System](../)
* Library [Aspose.Slides](../../)