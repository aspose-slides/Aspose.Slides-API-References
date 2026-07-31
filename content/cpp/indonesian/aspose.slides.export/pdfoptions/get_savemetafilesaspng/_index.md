---
title: get_SaveMetafilesAsPng()
second_title: Referensi API Aspose.Slides untuk C++
description: True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca bool.
type: docs
weight: 326
url: /id/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() metode

True to convert all metafiles used in a presentation to the PNG images. Read **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Keterangan

Nilai default adalah **true**. Dokumen Pdf dapat berisi grafik vektor dan gambar raster. Jika SaveMetafilesAsPng diatur ke true maka gambar Metafile sumber dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Sebagai contoh, jika Metafile dikonversi ke PNG, maka beberapa kehilangan kualitas dapat terjadi selama penskalaan dokumen yang dihasilkan. Jika Metafile dikonversi ke grafik vektor Pdf, maka masalah kinerja pada alat penampil Pdf dapat terjadi. 

## Lihat Juga

* Kelas [PdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)