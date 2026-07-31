---
title: SmartPtr
second_title: Referensi API Aspose.Slides untuk C++
description: "kelas pointer untuk membungkus tipe yang dialokasikan di heap. Gunakan untuk mengelola memori bagi kelas yang mewarisi Object. Tipe pointer ini mengikuti semantik pointer intrusif. Penghitung referensi disimpan baik di dalam Object sendiri atau dalam struktur penghitung yang terikat erat pada instance Object. Dalam hal apapun, semua instance SmartPtr membentuk grup kepemilikan tunggal terlepas dari bagaimana mereka dibuat, yang berbeda dengan perilaku kelas std::shared_ptr. Mengonversi pointer mentah ke SmartPtr aman asalkan ada instance SmartPtr lain yang memegang referensi bersama ke objek yang sama. Instance kelas SmartPtr dapat berada dalam satu dari dua keadaan: shared pointer dan weak pointer. Untuk menjaga objek tetap hidup, jumlah referensi bersama kepadanya harus positif. Baik pointer lemah maupun pointer bersama dapat digunakan untuk mengakses objek yang ditunjuk (untuk memanggil metode, membaca atau menulis bidang, dll.), tetapi pointer lemah tidak berpartisipasi dalam penghitung referensi pointer bersama. Object dihapus ketika pointer 'shared' SmartPtr terakhir ke objek tersebut dihancurkan. Jadi, pastikan hal ini tidak terjadi ketika tidak ada pointer SmartPtr bersama lain ke objek, misalnya selama konstruksi atau destruksi objek. Gunakan objek pengawas System::Object::ThisProtector (dalam kode C++) atau atribut CppCTORSelfReference atau CppSelfReference (dalam kode C# yang diterjemahkan) untuk memperbaiki masalah ini. Demikian pula, pastikan memutus referensi siklus dengan menggunakan kelas pointer System::WeakPtr atau mode pointer System::SmartPtrMode::Weak (dalam kode C++) atau atribut CppWeakPtr (dalam kode C# yang diterjemahkan). Jika dua atau lebih objek saling merujuk menggunakan pointer 'shared', mereka tidak akan pernah dihapus. Jika tipe pointer (lemah atau bersama) harus diubah pada runtime, gunakan metode System::SmartPtr<T>::set_Mode() atau kelas System::DynamicWeakPtr. Kelas SmartPtr tidak mengandung metode virtual apa pun. Anda hanya boleh mewarisinya jika Anda membuat strategi manajemen memori sendiri. Tipe ini adalah pointer untuk mengelola penghapusan objek lain. Harus dialokasikan pada stack dan diteruskan ke fungsi baik dengan nilai atau dengan referensi konstan."
type: docs
weight: 1236
url: /id/system/smartptr/
---
## SmartPtr kelas


Kelas pointer untuk membungkus tipe yang dialokasikan di heap. Gunakan untuk mengelola memori bagi kelas yang mewarisi [Object](../object/). Tipe pointer ini mengikuti semantik pointer intrusif. Penghitung referensi disimpan baik di dalam [Object](../object/) sendiri atau dalam struktur penghitung yang terikat erat pada instance [Object](../object/). Dalam kasus apapun, semua instance [SmartPtr](./) membentuk grup kepemilikan tunggal terlepas dari bagaimana mereka dibuat, yang berbeda dengan perilaku kelas std::shared_ptr. Mengonversi pointer mentah ke [SmartPtr](./) aman asalkan ada instance [SmartPtr](./) lain yang memegang referensi bersama ke objek yang sama. Instance kelas [SmartPtr](./) dapat berada dalam satu dari dua keadaan: pointer bersama dan pointer lemah. Untuk menjaga objek tetap hidup, jumlah referensi bersama kepadanya harus positif. Baik pointer lemah maupun pointer bersama dapat digunakan untuk mengakses objek yang ditunjuk (untuk memanggil metode, membaca atau menulis bidang, dll.), tetapi pointer lemah tidak berpartisipasi dalam penghitung referensi pointer bersama. [Object](../object/) dihapus ketika pointer 'shared' [SmartPtr](./) terakhir ke objek tersebut dihancurkan. Jadi, pastikan hal ini tidak terjadi ketika tidak ada pointer [SmartPtr](./) bersama lain ke objek, misalnya selama konstruksi atau destruksi objek. Gunakan objek pengawas System::Object::ThisProtector (dalam kode C++) atau atribut CppCTORSelfReference atau CppSelfReference (dalam kode C# yang diterjemahkan) untuk memperbaiki masalah ini. Demikian pula, pastikan memutus referensi siklus dengan menggunakan kelas pointer [System::WeakPtr](../weakptr/) atau mode pointer [System::SmartPtrMode::Weak](../smartptrmode/) (dalam kode C++) atau atribut CppWeakPtr (dalam kode C# yang diterjemahkan). Jika dua atau lebih objek saling merujuk menggunakan pointer 'shared', mereka tidak akan pernah dihapus. Jika tipe pointer (lemah atau bersama) harus diubah pada runtime, gunakan metode [System::SmartPtr<T>::set_Mode()](./set_mode/) atau kelas [System::DynamicWeakPtr](../dynamicweakptr/). Kelas [SmartPtr](./) tidak mengandung metode virtual apapun. Anda hanya boleh mewarisinya jika Anda membuat strategi manajemen memori sendiri. Tipe ini adalah pointer untuk mengelola penghapusan objek lain. Harus dialokasikan pada stack dan diteruskan ke fungsi baik dengan nilai atau dengan referensi konstan.

```cpp
template<class T>class SmartPtr
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek yang ditunjuk. Harus berupa [System::Object](../object/) atau subclass darinya. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| auto [begin](./begin/)() | Akses untuk metode [begin()](./begin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [begin()](./begin/). |
| auto [begin](./begin/)() const | Akses untuk metode [begin()](./begin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [begin()](./begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Mengubah tipe pointer ke tipe dirinya sendiri. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Mengubah pointer ke tipe dasar menggunakan static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Mengubah pointer ke tipe turunan menggunakan dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Mengubah pointer ke tipe turunan menggunakan dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Akses untuk metode [cbegin()](./cbegin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [cbegin()](./cbegin/). |
| auto [cend](./cend/)() const | Akses untuk metode [cend()](./cend/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [cend()](./cend/). |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Mengubah pointer ke tipe berbeda menggunakan const_cast pada objek yang ditunjuk. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Mengubah pointer ke tipe berbeda menggunakan dynamic_cast pada objek yang ditunjuk. |
| auto [end](./end/)() | Akses untuk metode [end()](./end/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [end()](./end/). |
| auto [end](./end/)() const | Akses untuk metode [end()](./end/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [end()](./end/). |
| [Pointee_](./pointee_/) * [get](./get/)() const | Mendapatkan objek yang ditunjuk. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Mendapatkan mode pointer. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Mendapatkan objek yang ditunjuk, tetapi memastikan bahwa pointer berada dalam mode bersama. |
| int [get_shared_count](./get_shared_count/)() const | Mendapatkan jumlah pointer bersama yang ada ke objek yang direferensikan, termasuk yang saat ini. Memastikan pointer saat ini berada dalam mode bersama. |
| int [GetHashCode](./gethashcode/)() const | Memanggil [GetHashCode()](./gethashcode/) pada objek yang ditunjuk. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Mendapatkan objek yang sedang direferensikan (jika ada) atau melempar pengecualian. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Mendapatkan objek yang ditunjuk (jika ada) atau nullptr. Sama dengan [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Mendapatkan objek yang direferensikan. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Mendapatkan objek yang ditunjuk (jika ada) atau nullptr. Sama dengan [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek yang ditunjuk bertipe spesifik atau tipe anaknya. Mengikuti semantik 'is' C#. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Memeriksa apakah pointer menunjuk ke objek lain selain yang dimiliki (dibuat oleh konstruktor aliasing). |
| **bool** [IsShared](./isshared/)() const | Memeriksa apakah pointer berada dalam mode bersama. |
| **bool** [IsWeak](./isweak/)() const | Memeriksa apakah pointer berada dalam mode lemah. |
| explicit  [operator bool](./operator_bool/)() const | Memeriksa apakah pointer tidak null. |
| **bool** [operator!](./operator_not/)() const | Memeriksa apakah pointer null. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Mendapatkan referensi ke objek yang ditunjuk. Memastikan bahwa pointer tidak null. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Memungkinkan mengakses anggota objek yang direferensikan. |
| **bool** [operator<](./operator_less/)(Y *) const | Menyediakan semantik perbandingan kurang (<) untuk kelas [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Menyediakan semantik perbandingan kurang (<) untuk kelas [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Melakukan penugasan pindah (move-assign) pada objek [SmartPtr](./). x menjadi tidak dapat digunakan. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Menugaskan salin (copy-assign) pada objek [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Menugaskan salin pada objek [SmartPtr](./). Melakukan konversi tipe yang diperlukan. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Menetapkan pointer mentah ke objek [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Mengatur nilai pointer ke nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Memeriksa apakah pointer menunjuk ke nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Menghapus aliasing (yang dibuat oleh konstruktor aliasing) dari pointer, memastikan bahwa ia mengelola (jika bersama) atau melacak (jika lemah) objek yang sama yang ditunjuknya. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Mengatur objek yang ditunjuk. |
| void [reset](./reset/)() | Membuat pointer menunjuk ke nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Mengatur mode pointer. Mungkin mengubah penghitung referensi objek yang direferensikan. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Memanggil metode SetTemplateWeakPtr() pada objek yang ditunjuk (jika ada). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](./) dengan mode yang diperlukan. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](./) null-pointer dengan mode yang diperlukan. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Membuat [SmartPtr](./) yang menunjuk ke objek yang ditentukan, atau mengonversi pointer mentah ke [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](./) dengan konstruktor salin. Kedua pointer akan menunjuk ke objek yang sama setelahnya. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](./) dengan konstruktor salin. Kedua pointer akan menunjuk ke objek yang sama setelahnya. Melakukan konversi tipe jika diizinkan. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](./) dengan konstruktor pindah. Secara efektif, menukar dua pointer, jika keduanya berada dalam mode yang sama. x mungkin tidak dapat digunakan setelah pemanggilan. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Mengonversi tipe array yang direferensikan dengan membuat array baru dengan tipe berbeda. Berguna jika di C# terdapat cast tipe array yang tidak didukung di C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Menginisialisasi array kosong. Digunakan untuk menerjemahkan beberapa konstruksi kode C#. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Membuat sebuah [SmartPtr](./) yang berbagi informasi kepemilikan dengan nilai awal ptr, tetapi memegang pointer p yang tidak terkait dan tidak dikelola. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Mengubah pointer ke tipe berbeda menggunakan static_cast pada objek yang ditunjuk. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Mengonversi tipe pointer apa pun menjadi pointer ke [Object](../object/). Tidak memerlukan tipe Pointee_ lengkap. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Jalan pintas untuk mendapatkan objek [System::TypeInfo](../typeinfo/) bagi tipe Pointee_. |
|  [~SmartPtr](./~smartptr/)() | Menghancurkan objek [SmartPtr](./). Jika diperlukan, mengurangi penghitung referensi objek yang ditunjuk dan menghapus objek. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [Pointee_](./pointee_/) | Tipe yang ditunjuk. |
| [SmartPtr_](./smartptr_/) | Tipe smart pointer yang dispesialisasi. |
| [ArrayType](./arraytype/) | Sama dengan Pointee_, jika merupakan spesialisasi dari [System::Array](../array/), dan void jika tidak. |
| [ValueType](./valuetype/) | Tipe penyimpanan array yang ditunjuk. Hanya bermakna jika T merupakan spesialisasi dari [System::Array](../array/). |

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)