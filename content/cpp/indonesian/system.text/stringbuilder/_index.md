---
title: StringBuilder
second_title: Referensi API Aspose.Slides untuk C++
description: "Buffer untuk mengakumulasi string bagian per bagian. Tipe ini dapat dialokasikan baik di stack sebagai tipe nilai atau di heap menggunakan fungsi System::MakeObject(). Setelah objek dialokasikan, jangan pernah mencampur kedua kasus penggunaan ini: memiliki pointer SmartPtr ke objek yang dialokasikan di stack secara tegas dilarang."
type: docs
weight: 326
url: /id/system.text/stringbuilder/
---
## StringBuilder kelas


[Buffer](../../system/buffer/) untuk mengakumulasi string bagian per bagian. Tipe ini dapat dialokasikan baik di stack sebagai tipe nilai atau di heap menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Setelah objek dialokasikan, jangan pernah mencampur kedua kasus penggunaan ini: memiliki pointer [SmartPtr](../../system/smartptr/) pada objek yang dialokasikan di stack secara tegas dilarang.

```cpp
class StringBuilder : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Menambahkan karakter ke builder. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Menambahkan karakter ke builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Menambahkan array karakter ke builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Menambahkan potongan array karakter ke builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Menambahkan string ke builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Menambahkan potongan string ke builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Menambahkan representasi string objek ke builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Menambahkan konten builder ke builder. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Menambahkan nilai floating point ke builder. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Menambahkan nilai floating point ke builder. |
| [StringBuilder](./) * [Append](./append/)(int) | Menambahkan nilai integer ke builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Menambahkan nilai aritmetika ke builder. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Menambahkan representasi string nilai enum ke builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Menambahkan string terformat ke builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Menambahkan string terformat ke builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Menambahkan karakter baris baru ke builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Menambahkan string diikuti karakter baris baru ke builder. |
| [StringBuilder](./) * [Clear](./clear/)() | Menghapus semua karakter dari builder. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Menyalin data builder ke posisi array yang ada. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Memastikan kapasitas instance [System.Text.StringBuilder](./) ini setidaknya nilai yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap setara meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap setara meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| int [get_Capacity](./get_capacity/)() const | Mendapatkan kapasitas saat ini dari string builder. |
| int [get_Length](./get_length/)() const | Mendapatkan panjang string yang saat ini ada di builder. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | Mendapatkan karakter pada posisi yang ditentukan. |
| void [idx_set](./idx_set/)(int, char_t) | Mengatur karakter pada posisi yang ditentukan. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Menyisipkan string ke posisi tetap builder. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Menyisipkan string berulang ke posisi tetap builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Menyisipkan karakter ke posisi tetap builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Menyisipkan karakter ke posisi tetap builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Menyisipkan nilai ke posisi tetap builder. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan contoh tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan lock() C# untuk mengunci. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salinan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salinan subclass. |
| char_t [operator[]](./operator[]/)(int) const | Mendapatkan karakter pada posisi yang ditentukan. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Menghapus fragmen dari builder. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Mengganti substring melalui builder. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Mengganti substring melalui rentang builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Mengganti karakter melalui builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Mengganti karakter melalui rentang builder. |
| void [set_Capacity](./set_capacity/)(int) | Mengatur kapasitas saat ini dari string builder. |
| void [set_Length](./set_length/)(int) | Memotong atau memperpanjang string builder ke panjang yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(int) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Konstruktor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Mendapatkan string yang saat ini terdapat dalam builder. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Mendapatkan substring yang saat ini terdapat dalam builder. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan unlock() C# untuk membuka kunci. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan weak reference. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan weak reference. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
|  [~StringBuilder](./~stringbuilder/)() | Destruktor. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Namespace [System::Text](../)
* Perpustakaan [Aspose.Slides](../../)