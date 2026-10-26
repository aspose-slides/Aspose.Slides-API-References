---
title: Array()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat array kosong.
type: docs
weight: 1
url: /id/system/array/array/
---
## Array::Array() konstruktor

Membuat sebuah array kosong.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) konstruktor

Konstruktor pengisian.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| count | int | Ukuran awal array |
| init | const T\& | Nilai awal yang digunakan untuk mengisi array |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) konstruktor

Konstruktor pengisian.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ValueType | Tipe nilai awal |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Ukuran awal array |
| init | [ValueType](../valuetype/) | Nilai awal yang digunakan untuk mengisi array |

## Array::Array(int, const T) konstruktor

Konstruktor pengisian.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| count | int | Ukuran awal array |
| inits | const T | Nilai-nilai untuk mengisi array |

## Array::Array(vector_t\&&) konstruktor

Konstruktor pindah.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, elemen-elemennya diakuisisi oleh array |

## Array::Array(const vector_t\&) konstruktor

Konstruktor salin.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector untuk menyalin nilai dari |

## Array::Array(const std::vector\<Q\>\&) konstruktor

Membuat objek [Array](../) dan mengisinya dengan nilai yang disalin dari objek std::vector yang tipe nilainya sama dengan **T** tetapi berbeda dari **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe elemen pada objek std::vector yang akan disalin elemennya |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector untuk menyalin nilai dari |

## Array::Array(std::vector\<Q\>\&&) konstruktor

Membuat objek [Array](../) dan mengisinya dengan nilai yang dipindahkan dari objek std::vector yang tipe nilainya sama dengan **T** tetapi berbeda dari **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe elemen pada objek std::vector yang akan dipindahkan elemennya dari |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector untuk menyalin nilai dari |

## Array::Array(std::initializer_list\<UnderlyingType\>) konstruktor

Membuat objek [Array](../) dan mengisinya dengan nilai dari daftar inisialisasi yang ditentukan berisi elemen berjenis **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Daftar inisialisasi yang berisi elemen untuk mengisi array |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) konstruktor

Membuat objek [Array](../) dan mengisinya dengan nilai dari array yang ditentukan berisi elemen berjenis **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| InitArraySize | Jumlah elemen pada array **init**. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) untuk disalin ke dalam array yang sedang dibuat. |

## Array::Array(std::initializer_list\<bool\>, int) konstruktor

Membuat objek [Array](../) dan mengisinya dengan nilai dari daftar inisialisasi yang ditentukan berisi elemen berjenis bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Daftar inisialisasi yang berisi elemen untuk mengisi array |

## Lihat Juga

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Kelas [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)