---
title: GraphicsPath()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat instance baru dari kelas GraphicsPath dengan mode pengisian yang ditentukan.
type: docs
weight: 1
url: /id/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) konstruktor


Membuat instance baru dari kelas [GraphicsPath](../) dengan mode pengisian yang ditentukan.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Menentukan bagaimana interior jalur tertutup yang diwakili oleh objek yang dibuat harus diisi |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) konstruktor


Membuat instance baru dari objek [GraphicsPath](../) yang mewakili jalur yang ditentukan.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Array yang berisi titik-titik yang menentukan jalur yang akan diwakili oleh objek yang dibuat |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi nilai-nilainya yang menentukan jenis-jenis titik yang bersesuaian dalam array **pts** |
| fillMode | [FillMode](../../fillmode/) | Menentukan bagaimana interior jalur tertutup yang diwakili oleh objek yang dibuat harus diisi |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) konstruktor


Membuat instance baru dari objek [GraphicsPath](../) yang mewakili jalur yang ditentukan.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Array yang berisi titik-titik yang menentukan jalur yang akan diwakili oleh objek yang dibuat |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi nilai-nilainya yang menentukan jenis-jenis titik yang bersesuaian dalam array **pts** |
| fillMode | [FillMode](../../fillmode/) | Menentukan bagaimana interior jalur tertutup yang diwakili oleh objek yang dibuat harus diisi |

## GraphicsPath::GraphicsPath(const SkPath\&) konstruktor




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Lihat Juga

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [GraphicsPath](../)
* Kelas [Point](../../../system.drawing/point/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Ruang Nama [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)