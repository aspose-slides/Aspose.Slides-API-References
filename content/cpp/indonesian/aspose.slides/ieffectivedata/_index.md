---
title: IEffectiveData
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili objek tak dapat diubah yang berisi data efektif.
type: docs
weight: 2055
url: /id/aspose.slides/ieffectivedata/
---
## IEffectiveData kelas

Mewakili objek tak dapat diubah yang berisi data efektif.

```cpp
class IEffectiveData : public virtual System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instansi dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambahkan penghitung referensi bersama. Tidak seharusnya dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() const | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak seharusnya dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambahkan penghitung referensi lemah. Tidak seharusnya dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak seharusnya dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)