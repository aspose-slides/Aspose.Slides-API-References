---
title: ConvertAll()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat daftar elemen yang dikonversi ke tipe berbeda.
type: docs
weight: 352
url: /id/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) metode


Membuat daftar elemen yang dikonversi ke tipe berbeda.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| OutputType | Output list element type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Converter to use for items conversion. |

### Nilai Kembalian

Daftar baru yang berisi elemen yang telah dikonversi.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Kelas [List](../)
* Ruang Nama [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)