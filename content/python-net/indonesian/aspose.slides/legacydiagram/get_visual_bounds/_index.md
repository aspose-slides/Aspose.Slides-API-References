---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual bentuk yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah **aspose.slides.RectangleF** yang merepresentasikan batas visual bentuk dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Segiempat yang dikembalikan merepresentasikan batas yang sejajar sumbu dari semua konten
             yang dihasilkan oleh bentuk selama proses render dalam ruang koordinat slide.
            
             Batas-batas ini dapat berbeda dari batas model bentuk
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan dapat berisi koordinat negatif jika konten yang dirender melampaui
             asal slide.
            
             Batas visual memperhitungkan aspek-aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar garis dan sambungan,
             tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya
             yang memengaruhi penampilan akhir bentuk yang dirender.
            
             Batas yang dikembalikan tidak dipotong ke dalam segiempat slide.



### Lihat Juga
* kelas [`LegacyDiagram`](/slides/python-net/id/aspose.slides/legacydiagram)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)