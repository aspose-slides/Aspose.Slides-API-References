---
title: Nullable
second_title: Referensi API Aspose.Slides untuk C++
description: Deklarasi maju.
type: docs
weight: 1106
url: /id/system/nullable/
---
## Kelas Nullable


Deklarasi maju.

```cpp
template<typename T>class Nullable
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai dasar yang diperluas oleh kelas [Nullable](./) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini sama dengan nilai yang diwakili oleh objek [Nullable](./) yang ditentukan. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Menentukan apakah objek saat ini mewakili nilai apa pun. |
| T [get_Value](./get_value/)() const | Mengembalikan salinan nilai yang diwakili oleh objek saat ini. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Mengembalikan nilai yang diwakili oleh objek saat ini atau nilai yang ditentukan jika nilai yang diwakili oleh objek saat ini bernilai null. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Menentukan apakah objek saat ini mewakili nilai null. |
| [Nullable](./nullable/)() | Membuat sebuah instance yang mewakili nilai null. |
| [Nullable](./nullable/)(std::nullptr_t) | Membuat sebuah instance yang mewakili null. |
| [Nullable](./nullable/)(const T1\&) | Membuat sebuah instance dari kelas [Nullable](./) yang mewakili nilai yang ditentukan yang dikonversi (jika perlu) ke nilai tipe dasar T. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Membuat sebuah instance yang mewakili nilai yang diwakili oleh objek [Nullable](./) yang ditentukan. Objek nullable yang ditentukan mungkin mewakili nilai dengan tipe berbeda dari tipe dasar instance yang dibuat, dalam hal ini nilai yang diwakili dikonversi ke tipe T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Fungsi pembantu untuk memeriksa apakah ini dan **other** keduanya bukan null dan memanggil lambda jika demikian. Digunakan dalam implementasi. |
| [operator const T &](./operator_const_t__and/)() const | Mengembalikan referensi konstan ke nilai yang diwakili oleh objek saat ini. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Menentukan apakah nilai yang diwakili oleh objek saat ini tidak null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini tidak sama dengan nilai yang ditentukan. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini tidak sama dengan nilai yang diwakili oleh objek [Nullable](./) yang ditentukan. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Menerapkan [operator&=()](./operator_and_equal/) ke nilai yang diwakili oleh objek saat ini menggunakan nilai yang ditentukan sebagai argumen sisi kanan. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Mengembalikan instance yang dibangun secara default dari kelas Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | Menjumlahkan nilai nullable dan non-nullable. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Menjumlahkan nilai nullable. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Mengatur ulang objek saat ini sehingga mewakili nilai null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Menerapkan [operator+=()](./operator_plus_equal/) ke nilai yang diwakili oleh objek saat ini menggunakan nilai yang ditentukan sebagai argumen sisi kanan. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Menerapkan [operator+=()](./operator_plus_equal/) ke nilai yang diwakili oleh objek saat ini menggunakan nilai yang diwakili oleh objek [Nullable](./) yang ditentukan sebagai argumen sisi kanan. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Mengurangkan nilai nullable dan nilai yang berisi null. |
| auto [operator-](./operator_minus/)(const T1\&) const | Mengurangkan nilai nullable dan non-nullable. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Mengurangkan nilai nullable. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Mengembalikan sebuah instance dari kelas [Nullable](./) yang mewakili nilai null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Menerapkan [operator-=()](./operator_minus_equal/) ke nilai yang diwakili oleh objek saat ini menggunakan nilai yang ditentukan sebagai argumen sisi kanan. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Menerapkan [operator-=()](./operator_minus_equal/) ke nilai yang diwakili oleh objek saat ini menggunakan nilai yang diwakili oleh objek [Nullable](./) yang ditentukan sebagai argumen sisi kanan. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Selalu mengembalikan false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini kurang dari nilai yang ditentukan dengan menerapkan [operator<()](./operator_less/) pada nilai-nilai tersebut. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini kurang dari nilai yang diwakili oleh objek [Nullable](./) yang ditentukan dengan menerapkan [operator<()](./operator_less/) pada nilai-nilai tersebut. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Selalu mengembalikan false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini kurang atau sama dengan nilai yang ditentukan dengan menerapkan [operator<=()](./operator_less_equal/) pada nilai-nilai tersebut. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini kurang atau sama dengan nilai yang diwakili oleh objek [Nullable](./) yang ditentukan dengan menerapkan [operator<=()](./operator_less_equal/) pada nilai-nilai tersebut. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Menetapkan null ke objek saat ini. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Mengganti nilai yang saat ini diwakili oleh objek dengan nilai yang ditentukan. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Mengganti nilai yang saat ini diwakili oleh objek dengan nilai yang ditentukan. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Menentukan apakah nilai yang diwakili oleh objek saat ini null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini sama dengan nilai yang ditentukan. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini sama dengan nilai yang diwakili oleh objek [Nullable](./) yang ditentukan. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Selalu mengembalikan false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar dari nilai yang ditentukan dengan menerapkan [operator>()](./operator_greater/) pada nilai-nilai tersebut. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar dari nilai yang diwakili oleh objek [Nullable](./) yang ditentukan dengan menerapkan [operator>()](./operator_greater/) pada nilai-nilai tersebut. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Selalu mengembalikan false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar atau sama dengan nilai yang diwakili oleh objek yang ditentukan dengan menerapkan [operator>=()](./operator_greater_equal/) pada nilai-nilai tersebut. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar atau sama dengan nilai yang diwakili oleh objek [Nullable](./) yang ditentukan dengan menerapkan [operator>=()](./operator_greater_equal/) pada nilai-nilai tersebut. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Menerapkan [operator|=()](./operator_or_equal/) ke nilai yang diwakili oleh objek saat ini menggunakan nilai yang ditentukan sebagai argumen sisi kanan. |
| void [reset](./reset/)() | Mengatur nilai yang saat ini diwakili menjadi null. |
| void [set_Value](./set_value/)(const T\&) | Menetapkan nilai baru ke objek nullable. |
| [String](../string/) [ToString](./tostring/)() const | Mengonversi nilai yang diwakili oleh objek saat ini menjadi string. |
## Tipe Alias

| Tipe Alias | Deskripsi |
| --- | --- |
| [ValueType](./valuetype/) | Alias untuk tipe nilai yang diwakili oleh kelas ini. |
## Keterangan

Mewakili sebuah nilai dari tipe yang ditentukan yang dapat diberi nilai null. Tipe ini harus dialokasikan di stack dan diteruskan ke fungsi oleh nilai atau oleh referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek dari tipe ini.

## Lihat Juga

* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)