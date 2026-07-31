---
title: Sign()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan tanda dari nilai integral bertanda yang ditentukan.
type: docs
weight: 274
url: /id/system/mathf/sign/
---
## MathF::Sign(T) metode


Menentukan tanda dari nilai integral bertanda yang ditentukan.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe bilangan bulat bertanda |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai untuk menentukan tanda |

### Nilai Kembali

- 1 jika **value** kurang dari 0; 0 jika **value** sama dengan 0; 1 jika **value** lebih besar dari 0

## MathF::Sign(T) metode


Menentukan tanda dari nilai floating-point yang ditentukan.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe floating point dari argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai untuk menentukan tanda |

### Nilai Kembali

- 1 jika **value** kurang dari 0; 0 jika **value** sama dengan 0; 1 jika **value** lebih besar dari 0

## Lihat Juga

* Struktur [MathF](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)