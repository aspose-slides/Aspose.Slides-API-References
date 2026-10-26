---
title: GetVisualBounds()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan batas visual shape yang dihitung dari konten yang dirender.
type: docs
weight: 677
url: /id/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() metode


Mendapatkan batas visual dari shape yang dihitung dari konten yang dirender.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Nilai Kembalian

Sebuah [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) yang mewakili batas visual shape dalam koordinat slide.
## Keterangan


Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh shape selama rendering dalam ruang koordinat slide.

Batas-batas ini mungkin berbeda dari batas model shape ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) dan mungkin berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual memperhitungkan aspek-aspek terkait rendering seperti transformasi (misalnya, rotasi), lebar goresan dan sambungan, tata letak teks dan overflow, [SmartArt](../../../aspose.slides.smartart/) geometri, dan efek tata letak lainnya yang memengaruhi penampilan akhir shape yang dirender.

Batas yang dikembalikan tidak dipotong ke persegi panjang slide. 

## Lihat Juga

* Kelas [RectangleF](../../../system.drawing/rectanglef/)
* Kelas [Shape](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)