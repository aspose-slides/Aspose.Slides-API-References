---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual shape yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah **aspose.slides.RectangleF** yang mewakili batas visual shape dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Segi empat yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh shape selama rendering dalam ruang koordinat slide.

Batas-batas ini mungkin berbeda dari batas model shape ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan dapat berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual memperhitungkan aspek-aspek terkait rendering seperti transformasi (misalnya, rotasi), lebar dan sambungan goresan, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lain yang memengaruhi tampilan akhir shape yang dirender.

Batas yang dikembalikan tidak dipotong sesuai segi empat slide.



### Lihat Juga
* kelas [`SmartArtShape`](/slides/python-net/id/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/id/aspose.slides.smartart)
* perpustakaan [`Aspose.Slides`](/slides/python-net)