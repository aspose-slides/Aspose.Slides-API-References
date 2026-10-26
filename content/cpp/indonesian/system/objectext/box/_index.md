---
title: Box()
second_title: Referensi API Aspose.Slides untuk C++
description: Membungkus tipe nilai untuk konversi ke Object. Implementasi untuk tipe enum.
type: docs
weight: 40
url: /id/system/objectext/box/
---
## ObjectExt::Box(const T&) metode


Membungkus tipe nilai untuk konversi ke [Object](../../object/). Implementasi untuk tipe enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) value to box. |

### Nilai Kembali

Smart pointer ke objek yang menyimpan nilai yang dibungkus.

## ObjectExt::Box(const T&) metode


Membungkus tipe nilai untuk konversi ke [Object](../../object/). Implementasi untuk tipe non-enum.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Value type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | Value to box. |

### Nilai Kembali

Smart pointer ke objek yang menyimpan nilai yang dibungkus.

## ObjectExt::Box(const T&) metode


Membungkus tipe [Nullable](../../nullable/) untuk konversi ke [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Value type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | Value to box. |

### Nilai Kembali

Smart pointer ke objek yang menyimpan nilai yang dibungkus.

## ObjectExt::Box(const String&) metode


Membungkus nilai string.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | Value to box. |

### Nilai Kembali

Nilai yang dibungkus atau null, jika string sumber null.

## Lihat Juga

* Kelas [SmartPtr](../../smartptr/)
* Kelas [Object](../../object/)
* Kelas [ObjectExt](../)
* Kelas [String](../../string/)
* Struktur [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)