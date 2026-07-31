---
title: EqualityComparerAdapter
second_title: Referensi API Aspose.Slides untuk C++
description: "Adapter yang memungkinkan penggunaan IEqualityComparer dengan koleksi dan algoritma bergaya STL. Menggunakan IEqualityComparer, jika diatur. Jika tidak diatur, menggunakan operator ==, Object::Equals atau T::Equals, mana yang tersedia."
type: docs
weight: 664
url: /id/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter yang memungkinkan penggunaan [IEqualityComparer](../iequalitycomparer/) dengan koleksi dan algoritma bergaya STL. Menggunakan [IEqualityComparer](../iequalitycomparer/), jika diatur. Jika tidak diatur, menggunakan operator ==, [Object::Equals](../../system/object/equals/) atau T::Equals, mana yang tersedia.

```cpp
template<class T>class EqualityComparerAdapter
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang dibandingkan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Membuat adaptor yang tidak menggunakan pembanding apapun. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Membuat adaptor dengan pembanding yang diberikan. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Membandingkan dua objek. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Mengatur pembanding. |

## Lihat Juga

* Ruang nama [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)