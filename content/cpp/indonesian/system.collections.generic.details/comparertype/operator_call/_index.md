---
title: operator()()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan tipe nilai yang mengimplementasikan antarmuka IComparable.
type: docs
weight: 1
url: /id/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const metode

Membandingkan tipe nilai yang mengimplementasikan antarmuka [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe yang akan dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const Q\& | Nilai LHS. |
| b | const Q\& | Nilai RHS. |

### Nilai Kembalian

True jika **a** dianggap lebih kecil dari **b**, false sebaliknya.

## ComparerType::operator()(const Q\&, const Q\&) const metode

Membandingkan tipe nilai primitif dan objek yang tidak mengimplementasikan antarmuka [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe yang akan dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const Q\& | Nilai LHS. |
| b | const Q\& | Nilai RHS. |

### Nilai Kembalian

True jika **a** dianggap lebih kecil dari **b**, false sebaliknya.

## ComparerType::operator()(const Q\&, const Q\&) const metode

Membandingkan tipe titik mengambang.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe yang akan dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const Q\& | Nilai LHS. |
| b | const Q\& | Nilai RHS. |

### Nilai Kembalian

True jika **a** dianggap lebih kecil dari **b**, false sebaliknya.

## Lihat Juga

* Kelas [IComparable](../../../system/icomparable/)
* Struktur [has_method_compareto](../../has_method_compareto/)
* Struktur [ComparerType](../)
* Ruang nama [System::Collections::Generic::Details](../../)
* Perpustakaan [Aspose.Slides](../../../)