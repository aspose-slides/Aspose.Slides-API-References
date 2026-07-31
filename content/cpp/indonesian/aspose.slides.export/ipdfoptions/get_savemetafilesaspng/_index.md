---
title: get_SaveMetafilesAsPng()
second_title: Referensi API Aspose.Slides untuk C++
description: Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca bool.
type: docs
weight: 287
url: /id/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() metode


Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Keterangan


Bawaan adalah **true**. Dokumen Pdf dapat berisi grafik vektor dan gambar raster. Jika SaveMetafilesAsPng diatur ke true maka gambar Metafile sumber dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Misalnya, jika Metafile dikonversi ke PNG, maka beberapa kehilangan kualitas dapat terjadi selama penskalaan dokumen yang dihasilkan. Jika Metafile dikonversi ke grafik vektor Pdf, maka masalah kinerja pada alat penampil Pdf dapat terjadi. 

## Lihat Juga

* Kelas [IPdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)