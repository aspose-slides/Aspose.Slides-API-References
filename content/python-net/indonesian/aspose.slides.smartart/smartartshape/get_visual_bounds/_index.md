---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual bentuk yang dihitung dari konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual bentuk dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Keterangan

The returned rectangle represents the axis-aligned bounds of all content
             Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten
             produced by the shape during rendering in slide coordinate space.
             yang dihasilkan oleh bentuk selama proses render dalam ruang koordinat slide.

             
             These bounds may differ from the shape's model bounds
             Batas-batas ini mungkin berbeda dari batas model bentuk
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             dan mungkin berisi koordinat negatif jika konten yang dirender meluas
             beyond the slide origin.
             melewati asal slide.

             
             The visual bounds take into account rendering-related aspects such as
             Batas visual memperhitungkan aspek terkait rendering seperti
             transformations (for example, rotation), stroke width and joins,
             transformasi (misalnya, rotasi), lebar goresan dan sambungan,
             text layout and overflow, SmartArt geometry, and other layout effects
             tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya
             that influence the final rendered appearance of the shape.
             yang memengaruhi tampilan akhir bentuk yang dirender.

             
             The returned bounds are not clipped to the slide rectangle.
             Batas yang dikembalikan tidak dipotong ke persegi panjang slide.



### Lihat Juga
* kelas [`SmartArtShape`](/slides/python-net/id/aspose.slides.smartart/smartartshape)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides.smartart`](/slides/python-net/id/aspose.slides.smartart)
* pustaka [`Aspose.Slides`](/slides/python-net)