---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili sekumpulan delegate. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek dari tipe ini."
type: docs
weight: 1093
url: /id/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> kelas


Mewakili sekumpulan delegate. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan [System::SmartPtr](../smartptr/) kelas untuk mengelola objek dari tipe ini.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ReturnType | Tipe kembali dari entitas yang dapat dipanggil yang ditunjuk oleh setiap delegate dalam koleksi |
| ArgumentTypes | Daftar argumen dari entitas yang dapat dipanggil yang ditunjuk oleh setiap delegate dalam koleksi |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | BELUM DIIMPLEMENTASIKAN. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Menambahkan delegate yang ditentukan ke koleksi. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Menambahkan objek fungsi yang ditentukan ke koleksi delegate. Objek fungsi tersebut dikonversi ke tipe delegate Callback sebelum ditambahkan ke koleksi. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Menambahkan objek MulticastDelegate yang ditentukan ke koleksi delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Menambahkan metode non-statis yang ditentukan dari objek yang ditentukan ke koleksi delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Menambahkan metode non-statis yang ditentukan dari objek yang ditentukan ke koleksi delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Menghapus delegate yang ditentukan dari koleksi delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Menghapus metode non-statis yang ditentukan dari objek yang ditentukan dari koleksi delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Menghapus metode non-statis yang ditentukan dari objek yang ditentukan dari koleksi delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Menghapus objek MulticastDelegate yang ditentukan dari koleksi delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Menghapus semua delegate dari koleksi delegate. |
| **bool** [empty](./empty/)() const | Menentukan apakah koleksi delegate kosong. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | BELUM DIIMPLEMENTASIKAN. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Memanggil semua delegate yang saat ini ada dalam koleksi delegate. Delegate dipanggil dalam urutan yang sama seperti saat mereka ditambahkan ke koleksi. Metode ini memblokir sementara delegate sedang dieksekusi. |
| **bool** [IsNull](./isnull/)() const | Menentukan apakah koleksi delegate kosong. |
|  [MulticastDelegate](./multicastdelegate/)() | Membuat koleksi kosong. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Setara dengan konstruktor default. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Melakukan salinan dangkal dari koleksi delegate. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Konstruktor pemindahan. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Membuat sebuah instance dan menempatkan delegate yang ditentukan ke koleksi delegate. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Membuat sebuah instance dan menempatkan nilai yang ditentukan ke koleksi delegate. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Membuat sebuah instance dan menempatkan nilai yang ditentukan ke koleksi delegate. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Menentukan apakah koleksi delegate tidak kosong. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Menentukan apakah dua instance MulticastDelegate - objek saat ini dan objek yang ditentukan - tidak sama. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Memanggil semua delegate yang saat ini ada dalam koleksi delegate. Delegate dipanggil dalam urutan yang sama seperti saat mereka ditambahkan ke koleksi. Operator ini memblokir sementara delegate sedang dieksekusi. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Menambahkan delegate yang ditentukan ke koleksi. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Menghapus delegate yang ditentukan dari koleksi delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Menetapkan koleksi delegate yang diwakili oleh objek yang ditentukan ke objek saat ini. Akibatnya kedua objek menunjuk ke koleksi delegate yang sama. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Operator penugasan pemindahan. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Menentukan apakah koleksi delegate kosong. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Menentukan apakah dua instance MulticastDelegate - objek saat ini dan objek yang ditentukan - sama. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Membersihkan callback yang terkandung yang kosong (tidak memanggil apa pun). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Mengembalikan referensi ke objek [TypeInfo](../typeinfo/) yang mewakili informasi tipe kelas MulticastDelegate. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destruktor. |
## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [Callback](./callback/) | Tipe delegate yang diwakili oleh kelas MulticastDelegate. |
| [Function](./function/) | Tipe fungsi yang terkait dengan tanda tangan delegate. |

## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)