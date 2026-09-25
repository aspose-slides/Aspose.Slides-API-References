---
title: get_visual_bounds method
second_title: Aspose.Slides untuk Python melalui Referensi API .NET
description: 
type: docs
url: /id/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual dari shape yang dihitung berdasarkan konten yang dirender.

### Mengembalikan

Sebuah [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef) yang mewakili batas visual dari shape dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Keterangan

Persegi panjang yang dikembalikan mewakili batas yang sejajar sumbu dari semua konten
yang dihasilkan oleh shape selama proses rendering dalam ruang koordinat slide.

Batas-batas ini dapat berbeda dari model bounds shape
([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
dan dapat berisi koordinat negatif jika konten yang dirender melampaui
asal slide.

Batas visual memperhitungkan aspek-aspek terkait rendering seperti
transformasi (misalnya, rotasi), lebar dan sambungan stroke,
tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya
yang memengaruhi tampilan akhir shape yang dirender.

Batas yang dikembalikan tidak dipotong sesuai persegi panjang slide.



### Lihat Juga
* kelas [`LegacyDiagram`](/slides/python-net/id/aspose.slides/legacydiagram)
* kelas [`RectangleF`](/slides/python-net/id/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)