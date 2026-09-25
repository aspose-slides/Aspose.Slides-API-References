---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual shape yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual shape dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh shape selama perenderan dalam ruang koordinat slide.

Batas-batas ini mungkin berbeda dari batas model shape ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan dapat berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual memperhitungkan aspek-aspek terkait perenderan seperti transformasi (misalnya rotasi), lebar goresan dan sambungan, tata letak teks dan overflow, geometrik SmartArt, serta efek tata letak lainnya yang memengaruhi penampilan akhir shape yang dirender.

Batas yang dikembalikan tidak dipotong ke persegi panjang slide.



### Lihat Juga
* kelas [`Ink`](/slides/python-net/id/aspose.slides.ink/ink)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides.ink`](/slides/python-net/id/aspose.slides.ink)
* pustaka [`Aspose.Slides`](/slides/python-net)