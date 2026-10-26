---
title: FillPolygon()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen çokgenin içini belirtilen fırça kullanarak doldurur.
type: docs
weight: 417
url: /tr/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) metod

Belirtilen çokgenin içini belirtilen fırça kullanarak doldurur.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | [Brush](../../brush/) nesnesi, dolgunun parametrelerini belirler |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | çokgeni tanımlayan noktaları içeren dizi |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Doldurma modu |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) metod

Belirtilen çokgenin içini belirtilen fırça kullanarak doldurur.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | [Brush](../../brush/) nesnesi, dolgunun parametrelerini belirler |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | çokgeni tanımlayan noktaları içeren dizi |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Doldurma modu |

## Bakınız

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)