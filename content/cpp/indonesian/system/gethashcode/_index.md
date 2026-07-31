---
title: GetHashCode()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan kode hash untuk nilai skalar yang ditentukan.
type: docs
weight: 2484
url: /id/system/gethashcode/
---
## System::GetHashCode(const T\&) fungsi

Mengembalikan kode hash untuk nilai skalar yang ditentukan.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe nilai untuk mana fungsi menghasilkan kode hash |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | Nilai untuk menghasilkan kode hash |

### Nilai Kembali

Kode hash yang dihasilkan untuk nilai yang ditentukan

## System::GetHashCode(const T\&) fungsi

Mengembalikan kode hash untuk objek yang ditentukan.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek untuk mana fungsi menghasilkan kode hash |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../smartptr/) yang menunjuk ke objek untuk menghasilkan kode hash |

### Nilai Kembali

Kode hash yang dihasilkan untuk objek yang ditentukan

## System::GetHashCode(const T\&) fungsi

Mengembalikan kode hash untuk objek yang ditentukan yang merupakan pengecualian.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek untuk mana fungsi menghasilkan kode hash |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | Exception Wrapper yang berisi objek untuk menghasilkan kode hash |

### Nilai Kembali

Kode hash yang dihasilkan untuk objek yang ditentukan

## System::GetHashCode(const T\&) fungsi

Mengembalikan kode hash untuk objek yang ditentukan yang bukan smart pointer maupun pengecualian.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek untuk mana fungsi menghasilkan kode hash |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | Referensi konstan ke objek untuk menghasilkan kode hash |

### Nilai Kembali

Kode hash yang dihasilkan untuk objek yang ditentukan

## System::GetHashCode(const std::thread::id\&) fungsi

Spesialisasi untuk std::thread::id; Mengembalikan kode hash untuk objek thread yang ditentukan.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Lihat Juga

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)