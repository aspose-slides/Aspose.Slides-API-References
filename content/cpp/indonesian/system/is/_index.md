---
title: Is()
second_title: Referensi API Aspose.Slides untuk C++
description: Menerapkan terjemahan pola deklarasi 'is'.
type: docs
weight: 2302
url: /id/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) fungsi


Menerapkan terjemahan pola deklarasi 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| PatternT | tipe untuk diperiksa. |
| ExpressionT | tipe ekspresi kiri. |
| ResultT | tipe hasil ekspresi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | const ExpressionT\& | ekspresi yang akan diperiksa. |
| result | ResultT\& | variabel yang akan diisi dengan tipe yang diperiksa. |

### Nilai Kembali

true jika pemeriksaan tipe berhasil, false jika tidak.

## System::Is(const ExpressionT\&, const ConstantT\&) fungsi


Menerapkan terjemahan pola konstan 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ExpressionT | tipe ekspresi kiri. |
| ConstantT | tipe ekspresi konstan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | const ExpressionT\& | ekspresi yang akan diperiksa. |
| constant | const ConstantT\& | ekspresi yang akan dibandingkan dengan yang kiri. |

### Nilai Kembali

true jika pemeriksaan tipe berhasil, false jika tidak.

## System::Is(const E\&, const A\&) fungsi


Fungsi pencocokan tingkat atas. Menerapkan pola pada sebuah nilai.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| A | Tipe pola (harus mewarisi Details::Pattern). |
| E | Tipe nilai yang akan dicocokkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| e | const E\& | Nilai yang akan dicocokkan. |
| a | const A\& | Pola yang akan diterapkan. |

### Nilai Kembali

true jika pola cocok dengan nilai.

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)