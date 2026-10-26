---
title: add_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk.  
Bentuk yang diklon mempertahankan posisi dan ukuran asli.

### Mengembalikan

[`IShape`](/slides/python-net/id/aspose.slides/ishape) yang baru dibuat.

```python
def add_clone(self, source_shape):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | [`IShape`](/slides/python-net/id/aspose.slides/ishape) yang akan diklon. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk.  
Bentuk baru mempertahankan lebar dan tinggi dari `source_shape`.

### Mengembalikan

[`IShape`](/slides/python-net/id/aspose.slides/ishape) yang baru dibuat.

```python
def add_clone(self, source_shape, x, y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | [`IShape`](/slides/python-net/id/aspose.slides/ishape) yang akan diklon. |
| x | **float** | Koordinat x dari frame bentuk yang diklon, dalam poin. |
| y | **float** | Koordinat y dari frame bentuk yang diklon, dalam poin. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk.

### Mengembalikan

[`IShape`](/slides/python-net/id/aspose.slides/ishape) yang baru dibuat.

```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | Bentuk yang akan diklon. |
| x | **float** | Koordinat x dari frame bentuk yang diklon, dalam poin. |
| y | **float** | Koordinat y dari frame bentuk yang diklon, dalam poin. |
| width | **float** | Lebar frame bentuk yang diklon, dalam poin. |
| height | **float** | Tinggi frame bentuk yang diklon, dalam poin. |

### Lihat Juga
* class [`IShape`](/slides/python-net/id/aspose.slides/ishape)
* class [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)