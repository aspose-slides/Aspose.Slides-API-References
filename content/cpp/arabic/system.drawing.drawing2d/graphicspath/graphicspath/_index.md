---
title: GraphicsPath()
second_title: Aspose.Slides لمرجع API C++
description: ينشئ نسخة جديدة من فئة GraphicsPath مع وضع التعبئة المحدد.
type: docs
weight: 1
url: /ar/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) المُنشئ

ينشئ نسخة جديدة من الفئة [GraphicsPath](../) مع وضع التعبئة المحدد.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | يحدد كيفية تعبئة الجزء الداخلي للمسار المغلق الذي يمثله الكائن الذي يتم إنشاؤه |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) المُنشئ

ينشئ نسخة جديدة من الكائن [GraphicsPath](../) الذي يمثل المسار المحدد.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | مصفوفة تحتوي على النقاط التي تحدد المسار الذي سيُمثله الكائن الذي يتم إنشاؤه |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة تحتوي على القيم التي تحدد أنواع النقاط المقابلة في مصفوفة **pts** |
| fillMode | [FillMode](../../fillmode/) | يحدد كيفية تعبئة الجزء الداخلي للمسار المغلق الذي يمثله الكائن الذي يتم إنشاؤه |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) المُنشئ

ينشئ نسخة جديدة من الكائن [GraphicsPath](../) الذي يمثل المسار المحدد.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | مصفوفة تحتوي على النقاط التي تحدد المسار الذي سيُمثله الكائن الذي يتم إنشاؤه |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة تحتوي على القيم التي تحدد أنواع النقاط المقابلة في مصفوفة **pts** |
| fillMode | [FillMode](../../fillmode/) | يحدد كيفية تعبئة الجزء الداخلي للمسار المغلق الذي يمثله الكائن الذي يتم إنشاؤه |

## GraphicsPath::GraphicsPath(const SkPath\&) المُنشئ




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## انظر أيضًا

* تعداد [FillMode](../../fillmode/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [GraphicsPath](../)
* فئة [Point](../../../system.drawing/point/)
* فئة [PointF](../../../system.drawing/pointf/)
* مساحة الاسم [System::Drawing::Drawing2D](../../)
* مكتبة [Aspose.Slides](../../../)