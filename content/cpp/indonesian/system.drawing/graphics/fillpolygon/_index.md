---
title: FillPolygon()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengisi bagian dalam poligon yang ditentukan menggunakan brush yang ditentukan.
type: docs
weight: 417
url: /id/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) metode

Mengisi bagian dalam poligon yang ditentukan menggunakan brush yang ditentukan.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Sebuah objek [Brush](../../brush/) yang menentukan parameter pengisian |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Array yang berisi titik-titik yang mendefinisikan poligon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Mode pengisian |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) metode

Mengisi bagian dalam poligon yang ditentukan menggunakan brush yang ditentukan.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Sebuah objek [Brush](../../brush/) yang menentukan parameter pengisian |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Array yang berisi titik-titik yang mendefinisikan poligon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Mode pengisian |

## Lihat Juga

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)