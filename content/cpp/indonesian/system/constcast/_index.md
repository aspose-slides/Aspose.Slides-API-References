---
title: ConstCast()
second_title: Referensi API Aspose.Slides untuk C++
description: Akhir dari cast yang tidak lagi disarankan.
type: docs
weight: 2575
url: /id/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) function

Akhir dari cast yang tidak lagi disarankan.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### Parameter Templat

| Parameter | Deskripsi |
| --- | --- |
| TTo | Tipe pointee target. |
| TFrom | Tipe pointee sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Penunjuk sumber. |

### Nilai Kembalian

Hasil cast jika cast diizinkan atau nullptr jika tidak.

## Catatan

Melakukan const cast pada objek [SmartPtr](../smartptr/).

## Lihat Juga

* Kelas [SmartPtr](../smartptr/)
* Struktur [CastResult](../castresult/)
* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)