---
title: DynamicWeakPtr
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas smart pointer yang melacak mode pointer dari argumen templat objek yang disimpan dan memperbaruinya setelah setiap penugasan. Tipe ini adalah pointer untuk mengelola penghapusan objek lain. Harus dialokasikan pada stack dan diteruskan ke fungsi baik dengan nilai maupun dengan referensi konstan.
type: docs
weight: 781
url: /id/system/dynamicweakptr/
---
## DynamicWeakPtr kelas


Smart pointer class yang melacak mode pointer dari argumen templat dari objek yang disimpan dan memperbaruinya setelah setiap penugasan. Tipe ini adalah pointer untuk mengelola penghapusan objek lain. Harus dialokasikan pada stack dan diteruskan ke fungsi baik dengan nilai maupun dengan referensi konstan.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Pointee | tipe. |
| trunkMode | Mode smart pointer itu sendiri, shared atau weak. |
| weakLeafs | Indeks argumen templat dari tipe yang disimpan yang harus diatur ke mode weak pointer. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Pengakses untuk metode [begin()](../smartptr/begin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Pengakses untuk metode [begin()](../smartptr/begin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Mengubah tipe pointer menjadi tipe itu sendiri. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Mengubah tipe pointer menjadi tipe dasar menggunakan static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Mengubah tipe pointer menjadi tipe turunan menggunakan dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Mengubah tipe pointer menjadi tipe turunan menggunakan dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Pengakses untuk metode [cbegin()](../smartptr/cbegin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Pengakses untuk metode [cend()](../smartptr/cend/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Mengubah pointer menjadi tipe berbeda menggunakan const_cast pada objek yang ditunjuk. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Mengubah pointer menjadi tipe berbeda menggunakan dynamic_cast pada objek yang ditunjuk. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Membuat smart pointer null. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Membuat smart pointer yang menunjuk ke objek yang diberikan. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Membuat salinan smart pointer melalui konstruktor salin. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Membuat salinan smart pointer melalui konstruktor salin. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Membuat salinan smart pointer melalui konstruktor salin. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Membuat smart pointer melalui konstruktor pindah. |
| auto [end](../smartptr/end/)() | Pengakses untuk metode [end()](../smartptr/end/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Pengakses untuk metode [end()](../smartptr/end/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ merupakan tipe spesialisasi dengan metode [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Mendapatkan objek yang ditunjuk. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Mendapatkan mode pointer. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Mendapatkan objek yang ditunjuk, tetapi memastikan pointer berada dalam mode shared. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Mendapatkan jumlah pointer shared yang ada pada objek yang direferensikan, termasuk yang saat ini. Memastikan pointer saat ini berada dalam mode shared. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Memanggil [GetHashCode()](../smartptr/gethashcode/) pada objek yang ditunjuk. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Mendapatkan objek yang saat ini direferensikan (jika ada) atau melemparkan pengecualian. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Mendapatkan objek yang ditunjuk (jika ada) atau nullptr. Sama dengan [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Mendapatkan objek yang direferensikan. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Mendapatkan objek yang ditunjuk (jika ada) atau nullptr. Sama dengan [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek yang ditunjuk berjenis tipe tertentu atau tipe turunan darinya. Mengikuti semantik 'is' C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Memeriksa apakah pointer menunjuk ke objek lain selain yang dimiliki (dibuat oleh konstruktor aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Memeriksa apakah pointer berada dalam mode shared. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Memeriksa apakah pointer berada dalam mode weak. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Memeriksa apakah pointer tidak null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Memeriksa apakah pointer null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Mendapatkan referensi ke objek yang ditunjuk. Memastikan pointer tidak null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Memungkinkan mengakses anggota dari objek yang direferensikan. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Memberikan semantik perbandingan kurang untuk kelas [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Memberikan semantik perbandingan kurang untuk kelas [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Menetapkan smart pointer dengan operasi pindah. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Menetapkan smart pointer dengan operasi salin. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Menetapkan smart pointer dengan operasi salin. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Menetapkan smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Menetapkan smart pointer menjadi null. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Memeriksa apakah smart pointer null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Menghapus aliasing (dibuat oleh konstruktor aliasing) dari pointer, memastikan ia mengelola (jika shared) atau melacak (jika weak) objek yang sama yang ditunjuknya. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Menetapkan objek yang ditunjuk. |
| void [reset](../smartptr/reset/)() | Membuat pointer menunjuk ke nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Menetapkan mode pointer. Dapat mengubah jumlah referensi objek yang direferensikan. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Memanggil metode SetTemplateWeakPtr() pada objek yang ditunjuk (jika ada). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](../smartptr/) dengan mode yang diperlukan. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](../smartptr/) null-pointer dengan mode yang diperlukan. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Membuat [SmartPtr](../smartptr/) yang menunjuk ke objek yang ditentukan, atau mengonversi pointer mentah ke [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](../smartptr/) dengan konstruktor salin. Kedua pointer akan menunjuk ke objek yang sama setelahnya. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](../smartptr/) dengan konstruktor salin. Kedua pointer akan menunjuk ke objek yang sama setelahnya. Melakukan konversi tipe jika diizinkan. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](../smartptr/) dengan konstruktor pindah. Secara efektif, menukar dua pointer, jika keduanya memiliki mode yang sama. x mungkin tidak dapat digunakan setelah pemanggilan. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Mengonversi tipe array yang direferensikan dengan membuat array baru dengan tipe berbeda. Berguna jika di C# ada cast tipe array yang tidak didukung di C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Menginisialisasi array kosong. Digunakan untuk menerjemahkan beberapa konstruksi kode C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Membuat sebuah [SmartPtr](../smartptr/) yang berbagi informasi kepemilikan dengan nilai awal ptr, namun memegang pointer p yang tidak terkait dan tidak dikelola. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Mengubah pointer menjadi tipe berbeda menggunakan static_cast pada objek yang ditunjuk. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Mengonversi tipe pointer apa pun menjadi pointer ke [Object](../object/). Tidak memerlukan tipe Pointee_ lengkap. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Pintasan untuk mendapatkan objek [System::TypeInfo](../typeinfo/) untuk tipe Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Menghancurkan objek [SmartPtr](../smartptr/). Jika diperlukan, mengurangi penghitung referensi objek yang ditunjuk dan menghapus objek. |
## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) alias kelas dasar. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | alias tipe diri. |
| [Pointee_](./pointee_/) | tipe yang ditunjuk. |

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)