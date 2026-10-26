---
title: ObjectToUnknown()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi Object ke tipe tidak diketahui, menangani baik tipe smart pointer maupun nilai bpxed.
type: docs
weight: 131
url: /id/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metode


Mengonversi [Object](../../object/) ke tipe tidak diketahui, menangani kedua tipe smart pointer dan situasi nilai bpxed.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe untuk mengonversi [Object](../../object/) menjadi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) untuk dikonversi. |

### Nilai Kembalian

Either unboxed value or converted pointer.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) metode


Mengonversi [Object](../../object/) ke tipe tidak diketahui, menangani kedua tipe smart pointer dan situasi nilai boxed.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe untuk mengonversi [Object](../../object/) menjadi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) untuk dikonversi. |

### Nilai Kembalian

Either unboxed value or converted pointer.

## Lihat Juga

* Kelas [SmartPtr](../../smartptr/)
* Kelas [Object](../../object/)
* Kelas [ObjectExt](../)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)