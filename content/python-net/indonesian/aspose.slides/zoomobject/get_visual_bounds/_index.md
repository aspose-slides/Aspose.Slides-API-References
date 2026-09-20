---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual bentuk yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah **aspose.slides.RectangleF** yang mewakili batas visual bentuk dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Segi empat yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh bentuk selama proses rendering dalam ruang koordinat slide.

Batas-batas ini dapat berbeda dari batas model bentuk ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan dapat berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual memperhitungkan aspek-aspek terkait rendering seperti transformasi (misalnya, rotasi), lebar garis dan sambungan, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lain yang memengaruhi tampilan akhir bentuk yang dirender.

Batas yang dikembalikan tidak dipotong ke segi empat slide.



### Lihat Juga
* kelas [`ZoomObject`](/slides/python-net/id/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)