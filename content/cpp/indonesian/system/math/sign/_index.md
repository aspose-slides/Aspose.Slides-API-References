---
title: Sign()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan tanda dari nilai integral bertanda yang ditentukan.
type: docs
weight: 274
url: /id/system/math/sign/
---
## Math::Sign(T) metode


Menentukan tanda dari nilai integral bertanda yang ditentukan.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe integral bertanda |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai untuk menentukan tanda |

### Return Value

- 1 jika **value** kurang dari 0; 0 jika **value** sama dengan 0; 1 jika **value** lebih besar dari 0

## Math::Sign(T) metode


Menentukan tanda dari nilai floating-point yang ditentukan.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe titik mengambang dari argumen |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai untuk menentukan tanda |

### Return Value

- 1 jika **value** kurang dari 0; 0 jika **value** sama dengan 0; 1 jika **value** lebih besar dari 0

## Math::Sign(const Decimal\&) metode


Menentukan tanda dari nilai desimal yang ditentukan.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Nilai untuk menentukan tanda |

### Return Value

- 1 jika **value** kurang dari 0; 0 jika **value** sama dengan 0; 1 jika **value** lebih besar dari 0

## Lihat Juga

* Kelas [Decimal](../../decimal/)
* Struktur [Math](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)