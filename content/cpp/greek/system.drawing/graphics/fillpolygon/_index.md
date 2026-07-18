---
title: FillPolygon()
second_title: Αναφορά API Aspose.Slides για C++
description: Γεμίζει τα εσωτερικά του καθορισμένου πολυγώνου χρησιμοποιώντας το καθορισμένο πινέλο.
type: docs
weight: 417
url: /el/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) μέθοδος

Γεμίζει τα εσωτερικά του καθορισμένου πολυγώνου χρησιμοποιώντας το καθορισμένο πινέλο.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object that specifies the parameters of the fill |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | An array containing the points that define the polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | The fill mode |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) μέθοδος

Γεμίζει τα εσωτερικά του καθορισμένου πολυγώνου χρησιμοποιώντας το καθορισμένο πινέλο.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object that specifies the parameters of the fill |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | An array containing the points that define the polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | The fill mode |

## Δείτε επίσης

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)