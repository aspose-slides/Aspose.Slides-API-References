---
title: SortedSetPtr
second_title: Referensi API Aspose.Slides untuk C++
description: Penunjuk untuk mempertahankan referensi SortedSet. Tipe ini adalah penunjuk untuk mengelola penghapusan objek lain. Seharusnya dialokasikan di stack dan diteruskan ke fungsi baik lewat nilai maupun lewat referensi konstan.
type: docs
weight: 586
url: /id/system.collections.generic/sortedsetptr/
---
## SortedSetPtr kelas


Penunjuk untuk mempertahankan referensi [SortedSet](../sortedset/). Tipe ini adalah penunjuk untuk mengelola penghapusan objek lain. Seharusnya dialokasikan di stack dan diteruskan ke fungsi baik lewat nilai maupun lewat referensi konstan.

```cpp
template<typename T>class SortedSetPtr : public System::SmartPtr<SortedSet<T>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Pengakses untuk metode [begin()](../../system/smartptr/begin/) dari koleksi dasar. Hanya dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Pengakses untuk metode [begin()](../../system/smartptr/begin/) dari koleksi dasar. Hanya dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Mengubah tipe penunjuk menjadi tipe dirinya sendiri. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Mengubah tipe penunjuk menjadi tipe dasar menggunakan static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Mengubah tipe penunjuk menjadi tipe turunan menggunakan dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Mengubah tipe penunjuk menjadi tipe turunan menggunakan dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Pengakses untuk metode [cbegin()](../../system/smartptr/cbegin/) dari koleksi dasar. Hanya dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Pengakses untuk metode [cend()](../../system/smartptr/cend/) dari koleksi dasar. Hanya dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Mengubah tipe penunjuk menjadi tipe lain menggunakan const_cast pada objek yang ditunjuk. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Mengubah tipe penunjuk menjadi tipe lain menggunakan dynamic_cast pada objek yang ditunjuk. |
| auto [end](../../system/smartptr/end/)() | Pengakses untuk metode [end()](../../system/smartptr/end/) dari koleksi dasar. Hanya dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Pengakses untuk metode [end()](../../system/smartptr/end/) dari koleksi dasar. Hanya dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Mendapatkan objek yang ditunjuk. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Mendapatkan mode penunjuk. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Mendapatkan objek yang ditunjuk, tetapi memastikan bahwa penunjuk berada dalam mode berbagi. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Mendapatkan jumlah penunjuk berbagi yang ada pada objek yang direferensikan, termasuk yang saat ini. Memastikan penunjuk saat ini berada dalam mode berbagi. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Memanggil [GetHashCode()](../../system/smartptr/gethashcode/) pada objek yang ditunjuk. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Mendapatkan objek yang saat ini direferensikan (jika ada) atau melempar pengecualian. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Mendapatkan objek yang ditunjuk (jika ada) atau nullptr. Sama dengan [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Mendapatkan objek yang direferensikan. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Mendapatkan objek yang ditunjuk (jika ada) atau nullptr. Sama dengan [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek yang ditunjuk berjenis tipe tertentu atau tipe turunan thereof. Mengikuti semantik C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Memeriksa apakah penunjuk menunjuk ke objek lain selain yang dimiliki (dibuat oleh konstruktor aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Memeriksa apakah penunjuk berada dalam mode berbagi. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Memeriksa apakah penunjuk berada dalam mode lemah. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Memeriksa apakah penunjuk tidak null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Memeriksa apakah penunjuk null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Mendapatkan referensi ke objek yang ditunjuk. Memastikan bahwa penunjuk tidak null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Memungkinkan mengakses anggota objek yang direferensikan. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Menyediakan semantik less-compare untuk kelas [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Menyediakan semantik less-compare untuk kelas [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Menetapkan pergerakan [SmartPtr](../../system/smartptr/) objek. x menjadi tidak dapat digunakan. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Menetapkan penyalinan [SmartPtr](../../system/smartptr/) objek. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Menetapkan penyalinan [SmartPtr](../../system/smartptr/) objek. Melakukan konversi tipe yang diperlukan. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Menetapkan penunjuk mentah ke objek [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Mengatur nilai penunjuk ke nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Memeriksa apakah penunjuk menunjuk ke nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Menghapus aliasing (dibuat oleh konstruktor aliasing) dari penunjuk, memastikan ia mengelola (jika berbagi) atau melacak (jika lemah) objek yang sama yang ditunjuknya. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Mengatur objek yang ditunjuk. |
| void [reset](../../system/smartptr/reset/)() | Membuat penunjuk menunjuk ke nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Mengatur mode penunjuk. Mungkin mengubah jumlah referensi objek yang direferensikan. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Memanggil metode SetTemplateWeakPtr() pada objek yang ditunjuk (jika ada). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Membuat objek [SmartPtr](../../system/smartptr/) dengan mode yang diperlukan. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Membuat objek [SmartPtr](../../system/smartptr/) penunjuk-nul dengan mode yang diperlukan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Membuat [SmartPtr](../../system/smartptr/) yang menunjuk ke objek yang ditentukan, atau mengonversi penunjuk mentah ke [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Menyalin konstruksi objek [SmartPtr](../../system/smartptr/). Kedua penunjuk menunjuk ke objek yang sama setelahnya. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Menyalin konstruksi objek [SmartPtr](../../system/smartptr/). Kedua penunjuk menunjuk ke objek yang sama setelahnya. Melakukan konversi tipe jika diizinkan. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Mengerakkan konstruksi objek [SmartPtr](../../system/smartptr/). Pada dasarnya menukar dua penunjuk, jika keduanya berada dalam mode yang sama. x mungkin tidak dapat digunakan setelah pemanggilan. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Mengonversi tipe array yang direferensikan dengan membuat array baru bertipe berbeda. Berguna bila di C# terdapat casting array yang tidak didukung di C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Menginisialisasi array kosong. Digunakan untuk menerjemahkan beberapa konstruksi kode C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Membuat sebuah [SmartPtr](../../system/smartptr/) yang berbagi informasi kepemilikan dengan nilai awal ptr, namun memegang penunjuk p yang tidak terkait dan tidak dikelola. |
|  [SortedSetPtr](./sortedsetptr/)() | Konstruktor penunjuk null. |
|  [SortedSetPtr](./sortedsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedSet](../sortedset/)\<T\>\>\&) | Konstruktor penyalinan. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Mengubah tipe penunjuk menjadi tipe lain menggunakan static_cast pada objek yang ditunjuk. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Mengonversi tipe penunjuk apa pun menjadi penunjuk ke [Object](../../system/object/). Tidak memerlukan tipe Pointee_ lengkap. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Shortcut untuk mendapatkan objek [System::TypeInfo](../../system/typeinfo/) bagi tipe Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Menghancurkan objek [SmartPtr](../../system/smartptr/). Jika diperlukan, mengurangi penghitung referensi objek yang ditunjuk dan menghapus objek. |

## Lihat Juga

* Kelas [SmartPtr](../../system/smartptr/)
* Ruang Nama [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)