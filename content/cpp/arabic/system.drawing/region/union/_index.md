---
title: Union()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة عملية الاتحاد بين هذه المنطقة ومنطقة معرفة بالمستطيل المحدد.
type: docs
weight: 53
url: /ar/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) طريقة

يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة عملية الاتحاد بين هذه المنطقة ومنطقة معرفة بالمستطيل المحدد.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### الوسائط

| معلمة | نوع | وصف |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | مستطيل يعرّف منطقة لتوحيد هذه المنطقة معها |

## Region::Union(const Rectangle\&) طريقة

يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة اتحاد هذه المنطقة ومنطقة معرفة بالمستطيل المحدد.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### الوسائط

| معلمة | نوع | وصف |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | مستطيل يعرّف منطقة لتوحيد هذه المنطقة معها |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) طريقة


يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة اتحاد هذه المنطقة ومنطقة معرفة بالمسار المحدد.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### الوسائط

| معلمة | نوع | وصف |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | مسار يعرّف منطقة لتوحيد هذه المنطقة معها |

## Region::Union(const SharedPtr\<Region\>\&) طريقة


يستبدل المنطقة التي يمثلها الكائن الحالي بنتيجة اتحاد هذه المنطقة والمنطقة المحددة.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### الوسائط

| معلمة | نوع | وصف |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | منطقة لتوحيد هذه المنطقة معها |

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [RectangleF](../../rectanglef/)
* فئة [Region](../)
* فئة [Rectangle](../../rectangle/)
* فئة [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)