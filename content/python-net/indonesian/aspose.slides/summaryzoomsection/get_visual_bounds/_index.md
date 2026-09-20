---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual dari shape yang dihitung dari kontennya yang dirender.

### Nilai Kembalian

Sebuah **aspose.slides.RectangleF** yang mewakili batas visual dari shape
             dalam koordinat slide.



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
             dan mungkin berisi koordinat negatif jika konten yang dirender melampaui
             asal slide.
            
             Batas visual memperhitungkan aspek-aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar dan sambungan goresan,
             tata letak teks dan kelebihan, geometri SmartArt, serta efek tata letak lain
             yang memengaruhi tampilan akhir shape yang dirender.
            
             Batas yang dikembalikan tidak dipotong ke dalam segi empat slide.



### Lihat Juga
* kelas [`SummaryZoomSection`](/slides/python-net/id/aspose.slides/summaryzoomsection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)