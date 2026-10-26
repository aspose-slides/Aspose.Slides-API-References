---
title: operator()()
second_title: Referensi API Aspose.Slides untuk C++
description: Fungsi perbandingan untuk tipe dengan operator < tersedia.
type: docs
weight: 27
url: /id/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const method


[Comparison](../../../system/comparison/) fungsi untuk tipe dengan operator < tersedia.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe yang dibandingkan; templat untuk ketersediaan konversi tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const Q\& | Nilai pertama untuk dibandingkan. |
| y | const Q\& | Nilai kedua untuk dibandingkan. |

### Nilai Kembali

True jika **x** dianggap kurang dari **y**, false otherwise.

## ComparerAdapter::operator()(const Q\&, const Q\&) const method


[Comparison](../../../system/comparison/) fungsi untuk tipe dengan operator < tidak tersedia.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe yang dibandingkan; templat untuk ketersediaan konversi tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const Q\& | Nilai pertama untuk dibandingkan. |
| y | const Q\& | Nilai kedua untuk dibandingkan. |

### Nilai Kembali

True jika comparator diatur dan **x** dianggap kurang dari **y**, false otherwise.

## Lihat Juga

* Struktur [ComparerAdapter](../)
* Ruang Nama [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)