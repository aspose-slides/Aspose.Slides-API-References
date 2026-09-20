---
title: save_metafiles_as_png property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png properti
True untuk mengonversi semua metafiles yang digunakan dalam presentasi menjadi gambar PNG.
            Baca/tulis **bool**.


### Catatan

Default adalah **true** .
            Dokumen Pdf dapat berisi grafik vektor dan gambar raster. 
            Jika SaveMetafilesAsPng diatur ke true maka gambar Metafile sumber dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster. Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber dikonversi menjadi grafik vektor Pdf. Setiap pendekatan memiliki kelebihan dan kekurangan. Sebagai contoh, jika Metafile dikonversi menjadi PNG, maka beberapa kehilangan kualitas dapat terjadi selama penskalaan dokumen yang dihasilkan. Jika Metafile dikonversi menjadi grafik vektor Pdf, maka masalah kinerja pada alat penampil Pdf dapat terjadi.

### Definisi:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### Lihat Juga
* kelas [`IPdfOptions`](/slides/python-net/id/aspose.slides.export/ipdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)