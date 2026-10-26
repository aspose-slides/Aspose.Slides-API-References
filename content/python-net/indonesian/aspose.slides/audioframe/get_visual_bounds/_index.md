---
title: get_visual_bounds method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual shape yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual dari shape dalam koordinat slide.

```python
def get_visual_bounds(self):
    ...
```

### Catatan

Segi empat yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten
             yang dihasilkan oleh shape selama rendering dalam ruang koordinat slide.

Batas-batas ini mungkin berbeda dari batas model shape
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan mungkin berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual memperhitungkan aspek-aspek terkait rendering seperti transformasi (misalnya, rotasi), lebar dan sambungan stroke, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lain yang memengaruhi tampilan akhir shape yang dirender.

Batas yang dikembalikan tidak dipotong sesuai segi empat slide.

### Lihat Juga
* class [`AudioFrame`](/slides/python-net/id/aspose.slides/audioframe)
* class [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)