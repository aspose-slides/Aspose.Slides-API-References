---
title: insert_picture_frame method
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Membuat sebuah frame gambar baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

### Mengembalikan

[`IPictureFrame`](/slides/python-net/id/aspose.slides/ipictureframe) yang baru dibuat.

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan frame gambar. |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | Menentukan tipe shape yang terkandung dalam [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype),<br/><br/>            kecuali semua jenis garis:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Koordinat x dari frame gambar, dalam satuan poin. |
| y | **float** | Koordinat y dari frame gambar, dalam satuan poin. |
| width | **float** | Lebar frame gambar, dalam satuan poin. |
| height | **float** | Tinggi frame gambar, dalam satuan poin. |
| image | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) yang akan ditampilkan dalam frame gambar. |

### Lihat Juga
* class [`IPictureFrame`](/slides/python-net/id/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage)
* class [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)