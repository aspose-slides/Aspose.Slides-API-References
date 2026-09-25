---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual dari bentuk yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual dari bentuk dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh bentuk selama proses rendering dalam ruang koordinat slide.

Batas-batas ini mungkin berbeda dari batas model bentuk ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan mungkin berisi koordinat negatif jika konten yang dirender melampaui asal slide.

Batas visual memperhitungkan aspek-aspek terkait rendering seperti transformasi (misalnya, rotasi), lebar dan sambungan goresan, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya yang memengaruhi tampilan akhir bentuk yang dirender.

Batas yang dikembalikan tidak dipotong ke dalam persegi panjang slide.



### Lihat Juga
* kelas [`SummaryZoomFrame`](/slides/python-net/id/aspose.slides/summaryzoomframe)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)