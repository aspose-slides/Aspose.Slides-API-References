---
title: Equals()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan kesetaraan nilai yang ditentukan menggunakan operator==().
type: docs
weight: 66
url: /id/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) fungsi

Menentukan kesetaraan nilai yang ditentukan menggunakan [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| The | tipe nilai yang sedang dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value1 | T | Komparan pertama |
| value2 | T | Komparan kedua |

### Nilai kembali

True jika nilai yang ditentukan sama sebagaimana ditentukan oleh [operator==()](../../system/operator_equal_equal/), jika tidak - false

## System::BoxedValueDetail::Equals(T, T) fungsi

Menentukan kesetaraan nilai yang ditentukan menggunakan metode [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| The | tipe nilai yang sedang dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value1 | T | Komparan pertama |
| value2 | T | Komparan kedua |

### Nilai kembali

True jika nilai yang ditentukan sama sebagaimana ditentukan oleh [Equals()](./), jika tidak - false

## Lihat Juga

* Ruang nama [System::BoxedValueDetail](../)
* Perpustakaan [Aspose.Slides](../../)