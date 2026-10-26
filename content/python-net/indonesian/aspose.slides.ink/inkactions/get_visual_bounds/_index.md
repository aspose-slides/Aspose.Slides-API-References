---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mengambil batas visual dari bentuk yang dihitung dari konten yang dirender.

### Mengembalikan
Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual dari bentuk
             dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan
Segi empat yang dikembalikan mewakili batas terpadu sumbu dari semua konten
             yang dihasilkan oleh bentuk selama rendering dalam ruang koordinat slide.
            
             Batas-batas ini mungkin berbeda dari batas model bentuk
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan mungkin berisi koordinat negatif bila konten yang dirender melampaui asal slide.
            
             Batas visual memperhitungkan aspek-aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar dan sambungan goresan,
             tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lain
             yang memengaruhi penampilan akhir bentuk yang dirender.
            
             Batas yang dikembalikan tidak dipotong ke segi empat slide.



### Lihat Juga
* kelas [`InkActions`](/slides/python-net/id/aspose.slides.ink/inkactions)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides.ink`](/slides/python-net/id/aspose.slides.ink)
* pustaka [`Aspose.Slides`](/slides/python-net)