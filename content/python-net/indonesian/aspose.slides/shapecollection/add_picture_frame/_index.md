---
title: add_picture_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Membuat sebuah bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk.

### Mengembalikan

[`IPictureFrame`](/slides/python-net/id/aspose.slides/ipictureframe) yang baru dibuat.

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | Menentukan jenis bentuk yang terdapat dalam [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype),<br/><br/>            kecuali semua jenis garis:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Koordinat x dari bingkai gambar, dalam poin. |
| y | **float** | Koordinat y dari bingkai gambar, dalam poin. |
| width | **float** | Lebar bingkai gambar, dalam poin. |
| height | **float** | Tinggi bingkai gambar, dalam poin. |
| image | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) yang akan ditampilkan dalam bingkai gambar. |

### Lihat Juga
* kelas [`IPictureFrame`](/slides/python-net/id/aspose.slides/ipictureframe)
* kelas [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* enumerasi [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)