---
title: get_visual_bounds method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Mendapatkan batas visual bentuk yang dihitung dari kontennya yang dirender.

### Returns
Mengembalikan

A **aspose.slides.RectangleF** yang mewakili batas visual bentuk
             dalam koordinat slide.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
Catatan

Persegi panjang yang dikembalikan mewakili batas sejajar sumbu
             dari semua konten yang dihasilkan oleh bentuk selama proses rendering dalam ruang koordinat slide.
            
             Batas-batas ini mungkin berbeda dari batas model bentuk
             ([`Shape.x`](/slides/python-net/id/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/id/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/id/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/id/aspose.slides/shape/height))
             dan dapat berisi koordinat negatif jika konten yang dirender melampaui asal slide.
            
             Batas visual memperhitungkan aspek-aspek terkait rendering seperti
             transformasi (misalnya, rotasi), lebar garis dan sambungan,
             tata letak teks dan overflow, geometri SmartArt, serta efek tata letak lainnya
             yang memengaruhi tampilan akhir bentuk yang dirender.
            
             Batas yang dikembalikan tidak dipotong ke persegi panjang slide.



### See Also
Lihat Juga
* class [`Chart`](/slides/python-net/id/aspose.slides.charts/chart)
* module [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)