---
title: Cast_noexcept()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan cast pada objek SmartPtr.
type: docs
weight: 2497
url: /id/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) fungsi


Melakukan cast pada objek [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe pointee target. |
| TFrom | Tipe pointee sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Pointer sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)