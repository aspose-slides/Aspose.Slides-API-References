---
title: ToString()
second_title: Referensi API Aspose.Slides untuk C++
description: Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.
type: docs
weight: 27
url: /id/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Nullable](../../nullable/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) objek untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(const T\&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Enum](../../enum/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) nilai untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(const T\&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe pointer pintar. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) nilai untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(T\&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe pointer pintar atau [ExceptionWrapper](../../exceptionwrapper/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T\& | Pointer pintar atau [ExceptionWrapper](../../exceptionwrapper/) untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(T\&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe skalar. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T\& | Nilai skalar untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(T\&&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe skalar. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T\&& | Nilai skalar untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(T\&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe struktur. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T\& | Nilai struktur untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(const T\&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe struktur. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | Nilai struktur untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## ObjectExt::ToString(T\&&) metode


Pengganti untuk metode ToString di C# agar dapat bekerja pada tipe C++ apa pun.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe skalar. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T\&& | Nilai skalar untuk dikonversi menjadi string. |

### Nilai Kembali

[String](../../string/) representasi dari **obj**.

## Lihat Juga

* Kelas [String](../../string/)
* Kelas [ObjectExt](../)
* Kelas [Nullable](../../nullable/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsNullable](../../isnullable/)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)