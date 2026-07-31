---
title: UnknownIsNull()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah objek tipe tidak diketahui adalah nullptr. Overload untuk tipe non-skalar.
type: docs
weight: 144
url: /id/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) metode

Memeriksa apakah objek tipe tidak diketahui adalah nullptr. Overload untuk tipe non-skalar.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../object/) tipe. |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T | [Object](../../object/) untuk diperiksa. |

### Return Value

True jika 'obj == nullptr' bernilai true, false sebaliknya.

## ObjectExt::UnknownIsNull(T) metode

Memeriksa apakah objek tipe tidak diketahui adalah nullptr. Overload untuk tipe skalar.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../object/) tipe. |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T | [Object](../../object/) untuk diperiksa. |

### Return Value

Selalu mengembalikan false.

## Lihat Juga

* Kelas [ObjectExt](../)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)