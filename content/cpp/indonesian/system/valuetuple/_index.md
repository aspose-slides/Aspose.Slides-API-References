---
title: ValueTuple
second_title: Aspose.Slides untuk Referensi API C++
description: Kelas yang merepresentasikan struktur data ValueTuple.
type: docs
weight: 1444
url: /id/system/valuetuple/
---
## ValueTuple kelas

Kelas yang merepresentasikan struktur data [ValueTuple](./).

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Menentukan apakah objek saat ini dan objek yang ditentukan identik. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Mendapatkan referensi ke nilai komponen objek [ValueTuple](./). |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Mendapatkan nilai komponen objek [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Mendeconstruct objek menjadi tuple nilai ini. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Mengembalikan referensi ke objek [TypeInfo](../typeinfo/) yang mewakili informasi tipe kelas [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) |  |

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)