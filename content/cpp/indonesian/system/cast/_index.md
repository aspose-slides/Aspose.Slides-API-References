---
title: Cast()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan cast pada objek SmartPtr.
type: docs
weight: 2510
url: /id/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) fungsi

Melakukan casting pada objek [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
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

Hasil cast jika casting diizinkan.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)