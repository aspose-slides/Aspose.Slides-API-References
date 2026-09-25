---
title: get_visual_bounds method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual bentuk yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual bentuk
             dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten
             yang dihasilkan oleh bentuk selama rendering dalam ruang koordinat slide.
            
             Batas-batas ini mungkin berbeda dari batas model bentuk
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan mungkin berisi koordinat negatif jika konten yang dirender melampaui asal slide.
            
             Batas visual memperhitungkan aspek-aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar dan sambungan goresan,
             tata letak teks dan overflow, geometri SmartArt, dan efek tata letak lain
             yang memengaruhi tampilan akhir bentuk yang dirender.
            
             Batas yang dikembalikan tidak dipotong ke dalam persegi slide.



### Lihat Juga
* kelas [`PictureFrame`](/slides/python-net/id/aspose.slides/pictureframe)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)