---
title: Exclude()
second_title: مرجع API Aspose.Slides للغة C++
description: يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة التي يحددها المستطيل المذكور منه.
type: docs
weight: 92
url: /ar/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) طريقة

يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة التي يُعرّفها المستطيل المحدد منه.

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | مستطيل يحدّد المنطقة التي يتم استبعادها |

## Region::Exclude(const Rectangle\&) طريقة

يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة التي يُعرّفها المستطيل المحدد منه.

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | مستطيل يحدّد المنطقة التي يتم استبعادها |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) طريقة

يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة التي يُعرّفها المسار المحدد منه.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | مسار يحدّد المنطقة التي يتم استبعادها |

## Region::Exclude(const SharedPtr\<Region\>\&) طريقة

يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة استبعاد المنطقة المحددة منه.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | منطقة يتم استبعادها |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [RectangleF](../../rectanglef/)
* فئة [Region](../)
* فئة [Rectangle](../../rectangle/)
* فئة [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)