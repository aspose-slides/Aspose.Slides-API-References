---
title: get_visual_bounds method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mengambil batas visual dari shape yang dihitung berdasarkan konten yang dirender.

### Mengembalikan

A **aspose.slides.RectangleF** yang mewakili batas visual dari shape
             dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan
Batas-batas ini mungkin berbeda dari batas model shape
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan mungkin berisi koordinat negatif jika konten yang dirender melampaui
             asal slide.

Batas visual memperhitungkan aspek-aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar garis dan sambungan,
             tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lain
             yang memengaruhi tampilan akhir shape yang dirender.

Batas yang dikembalikan tidak dipotong ke persegi panjang slide.



### Lihat Juga
* kelas [`InkActions`](/slides/python-net/id/aspose.slides.ink/inkactions)
* modul [`aspose.slides.ink`](/slides/python-net/id/aspose.slides.ink)
* perpustakaan [`Aspose.Slides`](/slides/python-net)