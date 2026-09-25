---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mengambil batas visual dari shape yang dihitung dari kontennya yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang merepresentasikan batas visual dari shape dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Segi empat yang dikembalikan merepresentasikan batas yang sejajar sumbu dari semua konten yang dihasilkan oleh shape selama proses rendering dalam ruang koordinat slide.

Batas-batas ini mungkin berbeda dari batas model shape ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan dapat berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual memperhitungkan aspek-aspek terkait rendering seperti transformasi (misalnya, rotasi), lebar garis dan sambungan, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya yang memengaruhi tampilan akhir shape yang dirender.

Batas yang dikembalikan tidak dipotong sesuai dengan segi empat slide.



### Lihat Juga
* kelas [`SmartArt`](/slides/python-net/id/aspose.slides.smartart/smartart)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides.smartart`](/slides/python-net/id/aspose.slides.smartart)
* perpustakaan [`Aspose.Slides`](/slides/python-net)