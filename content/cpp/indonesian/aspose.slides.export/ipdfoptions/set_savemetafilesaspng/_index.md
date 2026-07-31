---
title: set_SaveMetafilesAsPng()
second_title: Referensi API Aspose.Slides untuk C++
description: True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Tulis bool.
type: docs
weight: 300
url: /id/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) metode

True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Tulis **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Catatan

Default adalah **true**. Dokumen Pdf dapat berisi grafik vektor dan gambar raster. Jika SaveMetafilesAsPng diatur ke true maka gambar Metafile sumber dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Misalnya, jika Metafile dikonversi ke PNG, maka beberapa kehilangan kualitas mungkin terjadi selama penskalaan dokumen yang dihasilkan. Jika Metafile dikonversi ke grafik vektor Pdf, maka masalah kinerja pada alat penampil Pdf mungkin terjadi. 

## Lihat Juga

* Kelas [IPdfOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)