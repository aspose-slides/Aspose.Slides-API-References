---
title: Span
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili wilayah memori berkelanjutan yang arbitrer serupa dengan std::span pada C++20."
type: docs
weight: 1262
url: /id/system/span/
---
## Span kelas

Mewakili wilayah memori berkelanjutan yang arbitrer serupa dengan std::span pada C++20.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span. Kelas ini menyediakan cara aman-jenis untuk bekerja dengan urutan berkelanjutan objek. Dapat digunakan untuk membungkus array, array tumpukan, atau pointer mentah sambil mempertahankan pemeriksaan batas. [Span](./) tidak memiliki memori yang ditunjuknya - itu hanya tampilan ke memori yang ada. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Clear](./clear/)() const | Menghapus isi span dengan menetapkan semua elemen ke nilai default. |
| void [Fill](./fill/)(const T\&) const | Mengisi span dengan nilai yang ditentukan. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Mengonversi array menjadi [Span](./). |

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)