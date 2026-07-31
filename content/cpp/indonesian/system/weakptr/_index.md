---
title: WeakPtr
second_title: Aspose.Slides untuk Referensi API C++
description: "Subkelas dari System::SmartPtr yang mengatur dirinya ke mode lemah pada konstruksi. Harap catat bahwa kelas ini tidak menjamin bahwa instansinya akan selalu tetap dalam mode lemah karena set_Mode() masih dapat diakses. Tipe ini adalah pointer untuk mengelola penghapusan objek lain. Itu harus dialokasikan di stack dan diteruskan ke fungsi baik melalui nilai atau referensi const."
type: docs
weight: 1496
url: /id/system/weakptr/
---
## WeakPtr kelas

Subkelas dari [System::SmartPtr](../smartptr/) yang mengatur dirinya ke mode lemah pada konstruksi. Harap catat bahwa kelas ini tidak menjamin bahwa instansinya akan selalu tetap dalam mode lemah karena [set_Mode()](../smartptr/set_mode/) masih dapat diakses. Tipe ini adalah pointer untuk mengelola penghapusan objek lain. Itu harus dialokasikan di stack dan diteruskan ke fungsi baik melalui nilai maupun referensi const.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe pointee. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Pengakses untuk metode [begin()](../smartptr/begin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Pengakses untuk metode [begin()](../smartptr/begin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Mencast pointer ke tipe dirinya sendiri. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Mencast pointer ke tipe dasar menggunakan static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Mencast pointer ke tipe turunan menggunakan dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Mencast pointer ke tipe turunan menggunakan dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Pengakses untuk metode [cbegin()](../smartptr/cbegin/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Pengakses untuk metode [cend()](../smartptr/cend/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Mencast pointer ke tipe berbeda menggunakan const_cast pada objek yang dipoin. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Mencast pointer ke tipe berbeda menggunakan dynamic_cast pada objek yang dipoin. |
| auto [end](../smartptr/end/)() | Pengakses untuk metode [end()](../smartptr/end/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Pengakses untuk metode [end()](../smartptr/end/) dari koleksi yang mendasari. Hanya dapat dikompilasi jika SmartPtr_ adalah tipe spesialisasi dengan metode [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Memeriksa apakah objek yang direferensikan sudah dihapus. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Mendapatkan objek yang dipoin. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Mendapatkan mode pointer. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Mendapatkan objek yang dipoin, namun memastikan pointer berada dalam mode berbagi. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Mendapatkan jumlah pointer berbagi yang ada pada objek yang direferensikan, termasuk yang saat ini. Memastikan pointer saat ini berada dalam mode berbagi. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Mendapatkan objek yang direferensikan. Memastikan pointer berada dalam mode lemah. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Memanggil [GetHashCode()](../smartptr/gethashcode/) pada objek yang dipoin. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Mendapatkan objek yang saat ini direferensikan (jika ada) atau melemparkan exception. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Mendapatkan objek yang dipoin (jika ada) atau nullptr. Sama dengan [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Mendapatkan objek yang direferensikan. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Mendapatkan objek yang dipoin (jika ada) atau nullptr. Sama dengan [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek yang dipoin adalah tipe tertentu atau tipe turunannya. Mengikuti semantik 'is' pada C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Memeriksa apakah pointer menunjuk ke objek lain selain yang dimiliki (dibuat oleh konstruktor aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Memeriksa apakah pointer berada dalam mode berbagi. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Memeriksa apakah pointer berada dalam mode lemah. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Memeriksa apakah pointer tidak null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Memeriksa apakah pointer null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Mendapatkan referensi ke objek yang dipoin. Memastikan pointer tidak null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Mengizinkan akses ke anggota objek yang direferensikan. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Menyediakan semantik less-compare untuk kelas [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Menyediakan semantik less-compare untuk kelas [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Menetapkan nilai ke weak pointer. Memanggil operator penugasan spesifik dari SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Move-assign [SmartPtr](../smartptr/) objek. x menjadi tidak dapat digunakan. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Copy-assign [SmartPtr](../smartptr/) objek. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Copy-assign [SmartPtr](../smartptr/) objek. Melakukan konversi tipe yang diperlukan. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Menetapkan pointer mentah ke objek [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Mengatur nilai pointer menjadi nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Memeriksa apakah weak pointer null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Menghapus aliasing (dibuat oleh konstruktor aliasing) dari pointer, memastikan ia mengelola (jika shared) atau melacak (jika weak) objek yang sama yang ditunjuknya. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Mengatur objek yang dipoin. |
| void [reset](../smartptr/reset/)() | Membuat pointer menunjuk ke nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Mengatur mode pointer. Mungkin mengubah hitungan referensi objek yang direferensikan. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Memanggil metode SetTemplateWeakPtr() pada objek yang dipoin (jika ada). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](../smartptr/) dengan mode yang diperlukan. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Membuat objek [SmartPtr](../smartptr/) null-pointer dengan mode yang diperlukan. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Membuat [SmartPtr](../smartptr/) yang menunjuk ke objek yang ditentukan, atau mengkonversi pointer mentah ke [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Membuat konstruktor salin [SmartPtr](../smartptr/). Kedua pointer menunjuk ke objek yang sama setelahnya. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Membuat konstruktor salin [SmartPtr](../smartptr/). Kedua pointer menunjuk ke objek yang sama setelahnya. Melakukan konversi tipe jika diizinkan. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Membuat konstruktor move [SmartPtr](../smartptr/). Secara efektif, menukar dua pointer, bila keduanya dalam mode yang sama. x mungkin tidak dapat digunakan setelah panggilan. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Mengonversi tipe array yang direferensikan dengan membuat array baru dengan tipe yang berbeda. Berguna jika di C# ada cast tipe array yang tidak didukung di C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Menginisialisasi array kosong. Digunakan untuk menerjemahkan beberapa konstruksi kode C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Membuat [SmartPtr](../smartptr/) yang berbagi informasi kepemilikan dengan nilai awal ptr, tetapi memegang pointer p yang tidak terkait dan tidak dikelola. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Mencast pointer ke tipe berbeda menggunakan static_cast pada objek yang dipoin. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Mengonversi tipe pointer apa pun menjadi pointer ke [Object](../object/). Tidak memerlukan tipe Pointee_ lengkap. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Pintasan untuk mendapatkan objek [System::TypeInfo](../typeinfo/) untuk tipe Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Membuat pointer null. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Membuat weak pointer ke objek yang diberikan. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Membuat weak pointer yang mereferensikan pointer yang sama yang ditunjuk ptr. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Membuat weak pointer yang mereferensikan pointer yang sama yang ditunjuk x. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Membuat konstruktor salin weak pointer. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Membuat konstruktor salin weak pointer. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Membuat konstruktor move weak pointer. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Menghancurkan objek [SmartPtr](../smartptr/). Jika diperlukan, mengurangi penghitung referensi objek yang dipoin dan menghapus objek. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias untuk kelas [SmartPtr](../smartptr/) yang sesuai. |
| [WeakPtr_](./weakptr_/) | Alias untuk tipe diri sendiri. |
| [Pointee_](./pointee_/) | Tipe yang dipoin. |

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)