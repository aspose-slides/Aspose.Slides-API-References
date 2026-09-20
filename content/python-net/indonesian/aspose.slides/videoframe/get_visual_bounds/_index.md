---
title: get_visual_bounds method
second_title: Aspose.Slides untuk Python via .NET API Reference
description: 
type: docs
url: /id/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual shape yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah **aspose.slides.RectangleF** yang merepresentasikan batas visual shape dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Rectangel yang dikembalikan merepresentasikan batas yang sejajar sumbu dari semua konten yang dihasilkan oleh shape selama proses rendering dalam ruang koordinat slide.
Batas-batas ini mungkin berbeda dari batas model shape ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan dapat berisi koordinat negatif jika konten yang dirender melampaui asal slide.
Batas visual memperhitungkan aspek-aspek terkait rendering seperti transformasi (misalnya rotasi), lebar dan sambungan stroke, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya yang memengaruhi penampilan akhir shape yang dirender.
Batas yang dikembalikan tidak dipotong ke dalam persegi panjang slide.

### Lihat Juga
* kelas [`VideoFrame`](/slides/python-net/id/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)