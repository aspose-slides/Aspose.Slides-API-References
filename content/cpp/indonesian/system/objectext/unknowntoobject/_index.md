---
title: UnknownToObject()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi tipe yang tidak diketahui menjadi Object, menangani baik tipe pointer pintar maupun tipe nilai.
type: docs
weight: 118
url: /id/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) metode


Mengonversi tipe yang tidak diketahui menjadi [Object](../../object/), menangani baik situasi tipe pointer pintar maupun tipe nilai.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe untuk dikonversi menjadi [Object](../../object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T | [Object](../../object/) untuk dikonversi. |

### Nilai Kembali

Smart pointer ke [Object](../../object/) yang merupakan pointer yang dikonversi atau nilai yang dibungkus.

## ObjectExt::UnknownToObject(const T\&) metode


Mengonversi tipe yang tidak diketahui menjadi [Object](../../object/), menangani baik situasi tipe pointer pintar maupun tipe nilai.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe untuk dikonversi menjadi [Object](../../object/). |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) untuk dikonversi. |

### Nilai Kembali

Smart pointer ke [Object](../../object/) yang merupakan pointer yang dikonversi atau nilai yang dibungkus.

## Lihat Juga

* Kelas [SmartPtr](../../smartptr/)
* Kelas [Object](../../object/)
* Kelas [ObjectExt](../)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)