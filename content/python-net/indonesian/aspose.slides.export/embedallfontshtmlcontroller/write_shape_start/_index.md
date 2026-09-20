---
title: write_shape_start method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Dipanggil sebelum rendering shape. Dipanggil sekali untuk setiap shape. Jika fungsi ini menulis apa pun ke generator, proses pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan, dan gambar baru akan dimulai di atas gambar sebelumnya.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/id/aspose.slides.export/ihtmlgenerator) | Output object. |
| shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | Shape which is about to render. |



### Lihat Juga
* kelas [`EmbedAllFontsHtmlController`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller)
* kelas [`IHtmlGenerator`](/slides/python-net/id/aspose.slides.export/ihtmlgenerator)
* kelas [`IShape`](/slides/python-net/id/aspose.slides/ishape)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)