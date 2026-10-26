---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual shape yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual shape
             dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Segiempat yang dikembalikan mewakili batas berorientasi sumbu dari semua konten
             yang dihasilkan oleh shape selama proses render dalam ruang koordinat slide.
            
             Batas ini mungkin berbeda dari batas model shape
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan dapat berisi koordinat negatif jika konten yang dirender melampaui
             asal slide.
            
             Batas visual memperhitungkan aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar garis dan sambungan,
             tata letak teks dan overflow, geometri SmartArt, dan efek tata letak lain
             yang memengaruhi tampilan akhir shape yang dirender.
            
             Batas yang dikembalikan tidak dipotong ke segiempat slide.



### Lihat Juga
* kelas [`VideoFrame`](/slides/python-net/id/aspose.slides/videoframe)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)