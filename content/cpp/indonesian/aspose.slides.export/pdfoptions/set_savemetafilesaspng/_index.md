---
title: set_SaveMetafilesAsPng()
second_title: Referensi API Aspose.Slides untuk C++
description: Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Tulis bool.
type: docs
weight: 339
url: /id/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) metode

Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Tulis **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Catatan

Default adalah **true**. Dokumen Pdf dapat berisi grafik vektor dan gambar raster. Jika SaveMetafilesAsPng disetel ke true maka gambar Metafile sumber dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng disetel ke false maka Metafile sumber dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Misalnya, jika Metafile dikonversi ke PNG, maka beberapa kehilangan kualitas mungkin terjadi selama penskalaan dokumen hasil. Jika Metafile dikonversi ke grafik vektor Pdf, maka masalah kinerja pada alat penampil Pdf mungkin terjadi. 

## Lihat Juga

* Kelas [PdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)