---
title: ComparerType
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan elemen menggunakan semantik 'less'.
type: docs
weight: 144
url: /id/system.collections.generic.details/comparertype/
---
## ComparerType struct

Membandingkan elemen menggunakan semantik 'less'.

```cpp
template<typename T>class ComparerType
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen yang dibandingkan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Membandingkan tipe nilai yang mengimplementasikan antarmuka [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Membandingkan tipe nilai primitif dan objek yang tidak mengimplementasikan antarmuka [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Membandingkan tipe titik mengambang. |

## Lihat Juga

* Ruang nama [System::Collections::Generic::Details](../)
* Perpustakaan [Aspose.Slides](../../)