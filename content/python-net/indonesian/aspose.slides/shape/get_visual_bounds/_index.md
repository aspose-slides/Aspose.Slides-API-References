---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Mengambil batas visual bentuk yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual bentuk dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Catatan

Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten yang dihasilkan oleh bentuk selama perenderan di ruang koordinat slide.
            
Batas-batas ini mungkin berbeda dari batas model bentuk ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height)) dan mungkin mengandung koordinat negatif jika konten yang dirender melampaui asal slide.
            
Batas visual memperhitungkan aspek-aspek terkait perenderan seperti transformasi (misalnya rotasi), lebar garis dan sambungan, tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya yang memengaruhi tampilan akhir bentuk yang dirender.
            
Batas yang dikembalikan tidak dipotong sesuai persegi panjang slide.



### Lihat Juga
* class [`Shape`](/slides/python-net/id/aspose.slides/shape)
* class [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)