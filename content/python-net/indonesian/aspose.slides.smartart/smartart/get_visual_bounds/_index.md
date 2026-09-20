---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual dari bentuk yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah **aspose.slides.RectangleF** yang mewakili batas visual dari bentuk dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Persegi panjang yang dikembalikan mewakili batas sejajar sumbu dari semua konten
             yang dihasilkan oleh bentuk selama proses rendering dalam ruang koordinat slide.
            
             Batas ini dapat berbeda dari batas model bentuk
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan dapat berisi koordinat negatif jika konten yang dirender melampaui
             asal slide.
            
             Batas visual memperhitungkan aspek-aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar dan sambungan garis,
             tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya
             yang memengaruhi penampilan akhir bentuk yang dirender.
            
             Batas yang dikembalikan tidak dipotong ke persegi panjang slide.



### Lihat Juga
* kelas [`SmartArt`](/slides/python-net/id/aspose.slides.smartart/smartart)
* modul [`aspose.slides.smartart`](/slides/python-net/id/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)