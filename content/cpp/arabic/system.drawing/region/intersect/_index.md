---
title: Intersect()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يستبدل المنطقة التي يمثلها الكائن الحالي بالنتيجة الناتجة عن تقاطع هذه المنطقة ومنطقة معرفة بالمستطيل المحدد.
type: docs
weight: 79
url: /ar/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) method

يستبدل المنطقة التي يمثلها الكائن الحالي بالنتيجة الناتجة عن تقاطع هذه المنطقة ومنطقة معرفة بالمستطيل المحدد.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | مستطيل يحدد منطقة لتقاطع هذه المنطقة معها |

## Region::Intersect(const Rectangle\&) method

يستبدل المنطقة التي يمثلها الكائن الحالي بالنتيجة الناتجة عن تقاطع هذه المنطقة ومنطقة معرفة بالمستطيل المحدد.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | مستطيل يحدد منطقة لتقاطع هذه المنطقة معها |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method

يستبدل المنطقة التي يمثلها الكائن الحالي بالنتيجة الناتجة عن تقاطع هذه المنطقة ومنطقة معرفة بالمسار المحدد.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | مسار يحدد منطقة لتقاطع هذه المنطقة معها |

## Region::Intersect(const SharedPtr\<Region\>\&) method

يستبدل المنطقة التي يمثلها الكائن الحالي بالنتيجة الناتجة عن تقاطع هذه المنطقة والمنطقة المحددة.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | منطقة لتقاطع هذه المنطقة معها |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)