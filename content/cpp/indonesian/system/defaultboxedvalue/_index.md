---
title: DefaultBoxedValue
second_title: Referensi API Aspose.Slides untuk C++
description: "Implementasi kelas BoxedValue. Memungkinkan spesialisasi BoxingValue dideklarasikan tanpa menduplikasi kode umum. Objek kelas ini harus hanya dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kesalahan asersi. Selalu bungkus kelas ini menjadi penunjuk System::SmartPtr dan gunakan penunjuk ini untuk melewatkannya ke fungsi sebagai argumen."
type: docs
weight: 274
url: /id/system/defaultboxedvalue/
---
## DefaultBoxedValue kelas

[BoxedValue](../boxedvalue/) implementasi kelas. Memungkinkan spesialisasi BoxingValue dideklarasikan tanpa menduplikasi kode umum. Objek dari kelas ini harus hanya dialokasikan menggunakan fungsi [System::MakeObject()](../makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kesalahan asersi. Selalu bungkus kelas ini menjadi penunjuk [System::SmartPtr](../smartptr/) dan gunakan penunjuk ini untuk melewatkannya ke fungsi sebagai argumen.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Membuat sebuah instance baru dari kelas [DefaultBoxedValue](./) yang mewakili nilai yang ditentukan. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Menentukan kesetaraan nilai yang dibungkus yang direpresentasikan oleh objek saat ini dan objek yang ditentukan. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| int [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk objek saat ini. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Mendapatkan tipe sebenarnya dari objek. |
| **bool** [is](./is/)() const | Menentukan apakah tipe nilai yang dibungkus yang direpresentasikan oleh objek saat ini adalah **V**. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan penggandaan tipe khusus. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin kelas turunan. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin kelas turunan. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Menyetel argumen template ke-n menjadi penunjuk lemah (bukan berbagi). Memungkinkan mengubah penunjuk dalam kontainer ke mode lemah. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Menambahkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Mengembalikan representasi string dari nilai yang dibungkus. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../object/)). |
| const T\& [unbox](./unbox/)() const | Membuka kotak nilai yang dibungkus. |
| void [Unlock](../object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Menambahkan hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../object/)
* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)