---
title: IsVisible()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي.
type: docs
weight: 196
url: /ar/system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const طريقة

يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | const [Point](../../point/)\& | النقطة المراد فحصها |

## Region::IsVisible(const PointF\&) const طريقة

يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | النقطة المراد فحصها |

## Region::IsVisible(const Rectangle\&) طريقة

يحدد ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل المنطقة التي يمثلها الكائن الحالي.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | المستطيل المراد فحصه |

## Region::IsVisible(const RectangleF\&) طريقة

يحدد ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل المنطقة التي يمثلها الكائن الحالي.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | المستطيل المراد فحصه |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const طريقة

يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | const [Point](../../point/)\& | النقطة المراد فحصها |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | سياق الرسومات |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const طريقة

يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | النقطة المراد فحصها |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | سياق الرسومات |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) طريقة

يحدد ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | المستطيل المراد فحصه |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | سياق الرسومات |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) طريقة

يحدد ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | المستطيل المراد فحصه |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | سياق الرسومات |

## Region::IsVisible(float, float) const طريقة

يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X للنقطة المراد فحصها |
| y | **float** | الإحداثي Y للنقطة المراد فحصها |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const طريقة

يحدد ما إذا كانت النقطة المحددة موجودة داخل المنطقة التي يمثلها الكائن الحالي باستخدام الرسومات المحددة.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X للنقطة المراد فحصها |
| y | **float** | الإحداثي Y للنقطة المراد فحصها |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | سياق الرسومات |

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Point](../../point/)
* فئة [Region](../)
* فئة [PointF](../../pointf/)
* فئة [Rectangle](../../rectangle/)
* فئة [RectangleF](../../rectanglef/)
* فئة [Graphics](../../graphics/)
* مساحة الاسم [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)