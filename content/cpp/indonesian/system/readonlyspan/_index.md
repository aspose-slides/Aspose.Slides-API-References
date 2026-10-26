---
title: ReadOnlySpan
second_title: Referensi API Aspose.Slides untuk C++
description: Maju untuk digunakan dalam kelas Span.
type: docs
weight: 1210
url: /id/system/readonlyspan/
---
## ReadOnlySpan kelas

Maju untuk digunakan dalam [Span](../span/) kelas.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span. Kelas ini menyediakan cara yang aman-jenis untuk bekerja dengan urutan berkelanjutan objek dalam mode hanya-baca. Ini dapat digunakan untuk membungkus array, array stack, atau pointer mentah sambil mempertahankan pemeriksaan batas. [ReadOnlySpan](./) tidak memiliki memori yang ditunjuknya - itu hanya tampilan ke memori yang ada. |

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Membuat span hanya-baca dari span reguler. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Mengonversi array ke [ReadOnlySpan](./). |

## Catatan

Mewakili wilayah berkelanjutan hanya-baca dari memori sewenang-wenang.

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)