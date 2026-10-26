---
title: Complement()
second_title: مرجع Aspose.Slides للـ C++ API
description: يستبدل المنطقة الممثلة بالكائن الحالي بالجزء من المنطقة المعرفة بالمستطيل المحدد والذي لا يتقاطع مع هذه المنطقة.
type: docs
weight: 131
url: /ar/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) طريقة

يستبدل المنطقة الممثلة بالكائن الحالي بالجزء من المنطقة المحددة بالمستطيل المذكور والذي لا يتقاطع مع هذه المنطقة.

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | مستطيل يحدد المنطقة التي يتم استكمالها |

## Region::Complement(const Rectangle\&) طريقة

يستبدل المنطقة الممثلة بالكائن الحالي بالجزء من المنطقة المحددة بالمستطيل المذكور والذي لا يتقاطع مع هذه المنطقة.

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | مستطيل يحدد المنطقة التي يتم استكمالها |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) طريقة

يستبدل المنطقة الممثلة بالكائن الحالي بالجزء من المنطقة المحددة بالمسار المذكور والذي لا يتقاطع مع هذه المنطقة.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | مسار يحدد المنطقة التي يتم استكمالها |

## Region::Complement(const SharedPtr\<Region\>\&) طريقة


يستبدل المنطقة الممثلة بالكائن الحالي بالجزء من المنطقة المحددة والتي لا تتقاطع مع هذه المنطقة.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | منطقة لتكملتها |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [RectangleF](../../rectanglef/)
* فئة [Region](../)
* فئة [Rectangle](../../rectangle/)
* فئة [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)