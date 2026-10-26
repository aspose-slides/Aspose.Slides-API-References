---
title: UnboxToNullable()
second_title: Referensi API Aspose.Slides untuk C++
description: Melepaskan objek ke tipe nullable.
type: docs
weight: 79
url: /id/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) metode

Melepaskan objek ke tipe nullable.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe tujuan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) untuk unbox. |
| safe | **bool** | Jika true, mengembalikan nullptr pada kegagalan, jika tidak lempar InvalidCastException. |

### Nilai Kembali

Nilai nullable yang telah di-unbox (bisa null).

## Lihat Juga

* Kelas [Nullable](../../nullable/)
* Kelas [SmartPtr](../../smartptr/)
* Kelas [Object](../../object/)
* Kelas [ObjectExt](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)