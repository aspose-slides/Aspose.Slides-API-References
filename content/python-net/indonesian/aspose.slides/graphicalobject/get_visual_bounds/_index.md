---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual dari shape yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual shape
             dalam koordinat slide.

```python
def get_visual_bounds(self):
    ...
```

### Catatan

Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten
             yang dihasilkan oleh shape selama rendering dalam ruang koordinat slide.
             
             Batas ini mungkin berbeda dari batas model shape
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan dapat berisi koordinat negatif jika konten yang dirender melampaui
             asal slide.
             
             Batas visual memperhitungkan aspek-aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar dan sambungan garis,
             tata letak teks dan overflow, geometri SmartArt, dan efek tata letak lainnya
             yang memengaruhi tampilan akhir shape yang dirender.
             
             Batas yang dikembalikan tidak dipotong ke persegi panjang slide.

### Lihat Juga
* kelas [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)