---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual dari shape yang dihitung dari konten yang direndernya.

### Mengembalikan

Sebuah **aspose.slides.RectangleF** yang mewakili batas visual shape dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Rektangel yang dikembalikan mewakili batas sejajar sumbu dari semua konten yang dihasilkan oleh shape selama perenderan dalam ruang koordinat slide.

Batas ini mungkin berbeda dari batas model shape ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan mungkin berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual memperhitungkan aspek-aspek terkait perenderan seperti transformasi (misalnya, rotasi), lebar goresan dan sambungan, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya yang memengaruhi penampilan akhir shape yang dirender.

Batas yang dikembalikan tidak dipotong ke dalam rektangel slide.



### Lihat Juga
* kelas [`AutoShape`](/slides/python-net/id/aspose.slides/autoshape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)