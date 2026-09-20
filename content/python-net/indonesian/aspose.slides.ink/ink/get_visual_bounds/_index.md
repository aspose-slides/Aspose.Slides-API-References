---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ink/ink/get_visual_bounds/
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

Segiempat yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh bentuk selama proses rendering dalam ruang koordinat slide. Batas-batas ini mungkin berbeda dari batas model bentuk
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan dapat berisi koordinat negatif jika konten yang dirender melampaui
             asal slide.

             Batas visual memperhitungkan aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar goresan dan sambungan,
             tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya
             yang memengaruhi tampilan akhir bentuk yang dirender.

             Batas yang dikembalikan tidak dipotong ke persegi panjang slide.



### Lihat Juga
* kelas [`Ink`](/slides/python-net/id/aspose.slides.ink/ink)
* modul [`aspose.slides.ink`](/slides/python-net/id/aspose.slides.ink)
* perpustakaan [`Aspose.Slides`](/slides/python-net)