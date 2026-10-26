---
title: StringCollectionPtr
second_title: Referensi API Aspose.Slides untuk C++
description: Koleksi string pointer dengan operator akses.
type: docs
weight: 40
url: /id/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr kelas

Koleksi string pointer dengan operator akses.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Pengakses untuk metode [begin()](../../system/smartptr/begin/) dari koleksi dasar. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Pengakses untuk metode [begin()](../../system/smartptr/begin/) dari koleksi dasar. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Mengubah pointer ke tipe dirinya sendiri. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Mengubah pointer ke tipe dasar menggunakan static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Mengubah pointer ke tipe turunan menggunakan dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Mengubah pointer ke tipe turunan menggunakan dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Pengakses untuk metode [cbegin()](../../system/smartptr/cbegin/) dari koleksi dasar. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Pengakses untuk metode [cend()](../../system/smartptr/cend/) dari koleksi dasar. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Mengubah pointer ke tipe berbeda menggunakan const_cast pada objek yang ditunjuk. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Mengubah pointer ke tipe berbeda menggunakan dynamic_cast pada objek yang ditunjuk. |
| auto [end](../../system/smartptr/end/)() | Pengakses untuk metode [end()](../../system/smartptr/end/) dari koleksi dasar. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Pengakses untuk metode [end()](../../system/smartptr/end/) dari koleksi dasar. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Mendapatkan objek yang ditunjuk. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Mendapatkan mode pointer. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Mendapatkan objek yang ditunjuk, tetapi memastikan bahwa pointer berada dalam mode berbagi. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Mendapatkan jumlah pointer berbagi yang ada pada objek yang direferensikan, termasuk yang saat ini. Memastikan pointer saat ini berada dalam mode berbagi. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Memanggil [GetHashCode()](../../system/smartptr/gethashcode/) pada objek yang ditunjuk. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Mendapatkan objek yang direferensikan saat ini (jika ada) atau melempar pengecualian. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Mendapatkan objek yang ditunjuk (jika ada) atau nullptr. Sama dengan [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Mendapatkan objek yang direferensikan. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Mendapatkan objek yang ditunjuk (jika ada) atau nullptr. Sama dengan [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek yang ditunjuk merupakan tipe spesifik atau tipe anaknya. Mengikuti semantik 'is' C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Memeriksa apakah pointer menunjuk ke objek lain selain yang dimiliki (dibuat oleh konstruktor aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Memeriksa apakah pointer berada dalam mode berbagi. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Memeriksa apakah pointer berada dalam mode lemah. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Memeriksa apakah pointer tidak null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Memeriksa apakah pointer null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Mendapatkan referensi ke objek yang ditunjuk. Memastikan bahwa pointer tidak null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Memungkinkan mengakses anggota dari objek yang direferensikan. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Menyediakan semantik perbandingan kurang untuk kelas [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Menyediakan semantik perbandingan kurang untuk kelas [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Memindahkan penugasan objek [SmartPtr](../../system/smartptr/). x menjadi tidak dapat digunakan. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Menyalin penugasan objek [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Menyalin penugasan objek [SmartPtr](../../system/smartptr/). Melakukan konversi tipe yang diperlukan. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Menetapkan pointer mentah ke objek [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Mengatur nilai pointer menjadi nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Memeriksa apakah pointer menunjuk ke nullptr. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | Fungsi akses. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Menghapus aliasing (dibuat oleh konstruktor aliasing) dari pointer, memastikan bahwa pointer mengelola (jika berbagi) atau melacak (jika lemah) objek yang sama yang ditunjuknya. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Menetapkan objek yang ditunjuk. |
| void [reset](../../system/smartptr/reset/)() | Membuat pointer menunjuk ke nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Mengatur mode pointer. Dapat mengubah hitungan referensi objek yang direferensikan. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Memanggil metode SetTemplateWeakPtr() pada objek yang ditunjuk (jika ada). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Membuat objek [SmartPtr](../../system/smartptr/) dengan mode yang diperlukan. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Membuat objek [SmartPtr](../../system/smartptr/) null-pointer dengan mode yang diperlukan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Membuat [SmartPtr](../../system/smartptr/) yang menunjuk ke objek tertentu, atau mengubah pointer mentah menjadi [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Membuat konstruk kopi objek [SmartPtr](../../system/smartptr/). Kedua pointer menunjuk ke objek yang sama setelahnya. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Membuat konstruk kopi objek [SmartPtr](../../system/smartptr/). Kedua pointer menunjuk ke objek yang sama setelahnya. Melakukan konversi tipe jika diizinkan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Membuat konstruk pindah objek [SmartPtr](../../system/smartptr/). Secara efektif, menukar dua pointer, jika keduanya berada dalam mode yang sama. x mungkin tidak dapat digunakan setelah pemanggilan. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Mengubah tipe array yang direferensikan dengan membuat array baru dengan tipe berbeda. Berguna jika di C# ada casting tipe array yang tidak didukung di C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Menginisialisasi array kosong. Digunakan untuk menerjemahkan beberapa konstruk kode C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Membuat [SmartPtr](../../system/smartptr/) yang berbagi informasi kepemilikan dengan nilai awal ptr, tetapi memegang pointer p yang tidak terkait dan tidak dikelola. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Mengubah pointer ke tipe berbeda menggunakan static_cast pada objek yang ditunjuk. |
|  [StringCollectionPtr](./stringcollectionptr/)() | Membuat pointer null. |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | Membuat pointer ke koleksi tertentu. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Mengubah tipe pointer apa pun menjadi pointer ke [Object](../../system/object/). Tidak memerlukan tipe Pointee_ lengkap. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Jalan pintas untuk mendapatkan objek [System::TypeInfo](../../system/typeinfo/) untuk tipe Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Menghancurkan objek [SmartPtr](../../system/smartptr/). Jika diperlukan, mengurangi penghitung referensi objek yang ditunjuk dan menghapus objek. |
## Lihat Juga

* Kelas [SmartPtr](../../system/smartptr/)
* Ruang Nama [System::Collections::Specialized](../)
* Perpustakaan [Aspose.Slides](../../)