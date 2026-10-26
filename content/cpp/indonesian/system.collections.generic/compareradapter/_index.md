---
title: ComparerAdapter
second_title: Aspose.Slides untuk Referensi API C++
description: Adapter untuk menggunakan IComparer dalam lingkungan STL. Menggunakan IComparer jika disetel; jika tidak, menggunakan operator < (jika tersedia) atau mengembalikan false (jika tidak).
type: docs
weight: 638
url: /id/system.collections.generic/compareradapter/
---
## ComparerAdapter struct


Adapter untuk menggunakan [IComparer](../icomparer/) dalam lingkungan STL. Menggunakan [IComparer](../icomparer/) jika disetel; jika tidak, menggunakan operator < (jika tersedia) atau mengembalikan false (jika tidak).

```cpp
template<class T>class ComparerAdapter
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang dibandingkan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Membuat adapter tanpa komparator yang tersedia. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Membuat adapter. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | fungsi [Comparison](../../system/comparison/) untuk tipe dengan operator < tersedia. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | fungsi [Comparison](../../system/comparison/) untuk tipe tanpa operator <. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Menetapkan objek komparator. |

## Lihat Juga

* Ruang Nama [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)