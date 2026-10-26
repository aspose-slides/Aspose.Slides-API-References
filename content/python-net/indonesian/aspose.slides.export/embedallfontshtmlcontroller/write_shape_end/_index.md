---
title: write_shape_end method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Dipanggil sebelum rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas yang sebelumnya.

```python
def write_shape_end(self, generator, shape):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/id/aspose.slides.export/ihtmlgenerator) | Objek output. |
| shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | Bentuk yang dirender terakhir. |

### Lihat Juga
* kelas [`EmbedAllFontsHtmlController`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller)
* kelas [`IHtmlGenerator`](/slides/python-net/id/aspose.slides.export/ihtmlgenerator)
* kelas [`IShape`](/slides/python-net/id/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* pustaka [`Aspose.Slides`](/slides/python-net)