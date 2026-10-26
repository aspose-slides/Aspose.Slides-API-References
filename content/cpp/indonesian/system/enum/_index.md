---
title: Enum
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan metode yang melakukan beberapa operasi pada nilai tipe enum. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh membuat instansi darinya dengan cara apapun.
type: docs
weight: 1587
url: /id/system/enum/
---
## Struktur Enum


Menyediakan metode yang melakukan beberapa operasi pada nilai tipe enum. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh membuat instansi darinya dengan cara apapun.

```cpp
template<class E,class Guard>class Enum
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| E | Tipe enum yang nilai-nilainya ditangani oleh kelas |
| Guard | Argumen tipe layanan yang tujuannya memastikan bahwa **E** adalah tipe enumerable |
## Metode

| Metode | Deskripsi |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Melakukan perbandingan aritmetika dari nilai konstan enumerasi yang ditentukan. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Mengembalikan nama konstan enumerasi yang memiliki nilai yang ditentukan. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Mengembalikan nama konstan enumerasi yang memiliki nilai yang ditentukan. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Mengembalikan array yang berisi nama semua anggota enumerasi **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Mengembalikan tipe dasar dari enumerasi. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Mengembalikan array yang berisi semua anggota enumerasi **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Menentukan apakah bit yang ditentukan disetel dalam representasi bitari dari nilai enum yang ditentukan. |
| static **bool** [IsDefined](./isdefined/)(E) | Menentukan apakah nilai yang ditentukan merupakan anggota tipe enumerasi **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Menentukan apakah nilai yang ditentukan merupakan anggota tipe enumerasi **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Menentukan apakah nilai dengan nama yang ditentukan termasuk dalam anggota enum **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Mengonversi string yang ditentukan menjadi konstan enum yang setara. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Mencoba mengonversi string yang ditentukan menjadi konstan enum yang setara. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Mencoba mengonversi string yang ditentukan menjadi konstan enum yang setara. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias untuk tipe dasar enum. |

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)