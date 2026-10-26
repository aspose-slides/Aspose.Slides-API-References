---
title: EqualityComparerHashAdapter
second_title: Referensi API Aspose.Slides untuk C++
description: Adaptor untuk menggunakan IEqualityComparer untuk hashing. Menggunakan objek pembanding, jika diatur; jika tidak, menggunakan metode hash yang tersedia yang dipilih menggunakan DictionaryHashSelector struct.
type: docs
weight: 677
url: /id/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Adaptor untuk menggunakan [IEqualityComparer](../iequalitycomparer/) untuk hashing. Menggunakan objek pembanding, jika diatur; jika tidak, menggunakan metode hash yang tersedia yang dipilih menggunakan [DictionaryHashSelector](../dictionaryhashselector/) struct.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| Hashed | tipe. |

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Membuat adaptor tanpa pembanding untuk digunakan. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Membuat adaptor dengan pembanding yang diberikan untuk digunakan. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Menghitung nilai hash. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Mengatur pembanding yang akan digunakan. |

## Lihat Juga

* Namespace [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)