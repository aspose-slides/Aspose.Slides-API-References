---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual dari bentuk yang dihitung dari kontennya yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual dari bentuk dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Segi empat yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh bentuk selama proses rendering dalam ruang koordinat slide.

Batas-batas ini mungkin berbeda dari batas model bentuk ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan mungkin berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual mempertimbangkan aspek-aspek terkait rendering seperti transformasi (misalnya, rotasi), lebar dan sambungan garis, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya yang mempengaruhi tampilan akhir bentuk yang dirender.

Batas yang dikembalikan tidak dipotong ke segi empat slide.



### Lihat Juga
* kelas [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)