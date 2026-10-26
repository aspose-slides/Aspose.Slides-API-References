---
title: save_metafiles_as_png property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png properti
Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG.
            Baca/tulis **bool**.


### Catatan

Default adalah **true** .
            Dokumen Pdf dapat berisi grafik vektor dan gambar raster. 
            Jika SaveMetafilesAsPng diatur ke true maka Metafile sumber 
            gambar dikonversi ke format Png dan disimpan ke Pdf sebagai gambar raster 
            . Jika SaveMetafilesAsPng diatur ke false maka Metafile sumber 
            dikonversi ke grafik vektor Pdf. Setiap pendekatan memiliki kelebihan 
            dan kekurangan. Sebagai contoh, jika Metafile dikonversi ke PNG, 
            maka beberapa kehilangan kualitas mungkin terjadi selama penskalaan 
            dokumen hasil. Jika Metafile dikonversi ke grafik vektor Pdf, 
            maka masalah kinerja pada alat penampil Pdf mungkin terjadi.

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
* kelas [`PdfOptions`](/slides/python-net/id/aspose.slides.export/pdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)