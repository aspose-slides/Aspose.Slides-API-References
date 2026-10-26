---
title: ForceStaticCast()
second_title: Aspose.Slides untuk Referensi API C++
description: Melakukan cast statik nyata pada objek SmartPtr.
type: docs
weight: 2588
url: /id/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) fungsi

Melakukan cast statik nyata pada objek [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe pointee target. |
| TFrom | Tipe pointee sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Pointer sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan, jika tidak perilaku tidak terdefinisi.

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Struktur [CastResult](../castresult/)
* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)