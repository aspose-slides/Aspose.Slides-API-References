---
title: BoxedValue< ValueTuple< Args... > >
second_title: Referensi API Aspose.Slides untuk C++
description: Versi terbungkus dari tuple nilai.
type: docs
weight: 118
url: /id/system/boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/
---
## BoxedValue< ValueTuple< Args... > > kelas

Versi terbungkus dari tuple nilai.

```cpp
template<typename...>class BoxedValue< ValueTuple< Args... > > : public System::Runtime::CompilerServices::ITuple
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| name | Tipe elemen tuple Args. |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const [ValueT](../valuetuple/)\&) | Membuat objek [BoxedValue](../boxedvalue/) yang mewakili nilai terbungkus yang ditentukan. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Menentukan kesetaraan nilai terbungkus yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| int [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk objek saat ini. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Mendapatkan tipe aktual objek. |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | Mengembalikan elemen pada posisi indeks. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| **bool** [is](./is/)() const | Menentukan apakah tipe nilai terbungkus yang diwakili oleh objek saat ini adalah **V**. |
| void [Lock](../object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan penggandaan tipe khusus. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor penyalin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke- n menjadi pointer lemah (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Mengembalikan representasi string dari nilai terbungkus. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Menerapkan konstruksi C# typeof([System.Object](../object/)). |
| const [ValueT](../valuetuple/)\& [unbox](./unbox/)() const | Membuka nilai terbungkus. |
| void [Unlock](../object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [ITuple](../../system.runtime.compilerservices/ituple/)
* Namespace [System](../)
* Pustaka [Aspose.Slides](../../)