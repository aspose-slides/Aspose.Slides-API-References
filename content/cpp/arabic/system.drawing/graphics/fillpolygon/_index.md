---
title: FillPolygon()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يملأ داخل المضلّع المحدد باستخدام الفرشاة المحددة.
type: docs
weight: 417
url: /ar/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) طريقة

يملأ داخل المضلّع المحدد باستخدام الفرشاة المحددة.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | كائن [Brush](../../brush/) يحدد معلمات التعبئة |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | مصفوفة تحتوي على النقاط التي تُعرّف المضلّع |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | وضع التعبئة |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) طريقة

يملأ داخل المضلّع المحدد باستخدام الفرشاة المحددة.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | كائن [Brush](../../brush/) يحدد معلمات التعبئة |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | مصفوفة تحتوي على النقاط التي تُعرّف المضلّع |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | وضع التعبئة |

## انظر أيضًا

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)