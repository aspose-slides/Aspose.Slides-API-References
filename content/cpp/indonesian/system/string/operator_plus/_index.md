---
title: operator+()
second_title: Referensi API Aspose.Slides untuk C++
description: Operator penggabungan string.
type: docs
weight: 274
url: /id/system/string/operator_plus/
---
## String::operator+(const String\&) const metode

[String](../) operator penggabungan.
```cpp
String System::String::operator+(const String &str) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) untuk menambahkan ke akhir yang saat ini. |

### Nilai Kembali

String yang digabungkan.

## String::operator+(const T&) const metode

[String](../) penggabungan dengan literal string atau penunjuk string karakter.
```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Salah satu bentuk literal string atau penunjuk string karakter. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg | const T\& | Entitas untuk digabungkan dengan string saat ini. |

### Nilai Kembali

String yang digabungkan.

## String::operator+(char_t) const metode

Menambahkan karakter ke akhir string.
```cpp
String System::String::operator+(char_t x) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | char_t | Karakter untuk ditambahkan. |

### Nilai Kembali

[String](../) hasil penggabungan.

## String::operator+(int) const metode

Menambahkan representasi string nilai integer ke akhir string.
```cpp
String System::String::operator+(int i) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | int | Nilai integer yang dikonversi ke string dan ditambahkan. |

### Nilai Kembali

[String](../) hasil penggabungan.

## String::operator+(uint32_t) const metode

Menambahkan representasi string nilai unsigned integer ke akhir string.
```cpp
String System::String::operator+(uint32_t i) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | **uint32_t** | Nilai yang dikonversi ke string dan ditambahkan. |

### Nilai Kembali

[String](../) hasil penggabungan.

## String::operator+(double) const metode

Menambahkan representasi string nilai floating point ke akhir string.
```cpp
String System::String::operator+(double d) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| d | **double** | Nilai yang dikonversi ke string dan ditambahkan. |

### Nilai Kembali

[String](../) hasil penggabungan.

## String::operator+(int64_t) const metode

Menambahkan representasi string nilai integer ke akhir string.
```cpp
String System::String::operator+(int64_t v) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | **int64_t** | Nilai yang dikonversi ke string dan ditambahkan ke add. |

### Nilai Kembali

[String](../) hasil penggabungan.

## String::operator+(const T&) const metode

Menambahkan representasi string objek tipe referensi ke akhir string.
```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe penunjuk. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) untuk dikonversi ke string menggunakan panggilan [ToString()](../tostring/) dan ditambahkan ke string saat ini. |

### Nilai Kembali

[String](../) hasil penggabungan.

## String::operator+(const T&) const metode

Menambahkan representasi string objek tipe nilai ke akhir string.
```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai untuk memanggil [ToString()](../tostring/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) untuk dikonversi ke string menggunakan panggilan [ToString()](../tostring/) dan ditambahkan ke string saat ini. |

### Nilai Kembali

[String](../) hasil penggabungan.

## String::operator+(T) const metode

Menambahkan representasi string nilai boolean ke akhir string.
```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai untuk digabungkan dengan string. Harus bool |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) nilai untuk dikonversi ke string dan ditambahkan. |

### Nilai Kembali

[String](../) hasil penggabungan.

## Lihat Juga

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)