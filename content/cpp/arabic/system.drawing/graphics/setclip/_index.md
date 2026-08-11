---
title: SetClip()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتعيين منطقة القص لسطح الرسم الممثَّل بالكائن Graphics الحالي إلى نتيجة العملية المحددة التي تجمع بين منطقة القص الحالية والمنطقة المحددة.
type: docs
weight: 690
url: /ar/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) طريقة

يقوم بتعيين منطقة القص لسطح الرسم الممثَّل بالكائن [Graphics](../) الحالي إلى نتيجة العملية المحددة التي تجمع بين منطقة القص الحالية والمنطقة المحددة.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | يحدد منطقة للجمع |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | يحدد عملية الجمع |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) طريقة

يقوم بتعيين منطقة القص لسطح الرسم الممثَّل بالكائن [Graphics](../) الحالي إلى نتيجة العملية المحددة التي تجمع بين منطقة القص الحالية والمنطقة المحددة.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | يحدد منطقة للجمع |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | يحدد عملية الجمع |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) طريقة

يقوم بتعيين منطقة القص لسطح الرسم الممثَّل بالكائن [Graphics](../) الحالي إلى نتيجة العملية المحددة التي تجمع بين منطقة القص الحالية والمنطقة المحددة.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | يحدد منطقة للجمع |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | يحدد عملية الجمع |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) طريقة

غير مُنفّذ.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) طريقة

يقوم بتعيين منطقة القص لسطح الرسم الممثَّل بالكائن [Graphics](../) الحالي إلى نتيجة العملية المحددة التي تجمع بين منطقة القص الحالية والمنطقة المحددة بواسطة مسار رسومي.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | يحدد منطقة للجمع |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | يحدد عملية الجمع |

## انظر أيضًا

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Region](../../region/)
* فئة [Graphics](../)
* فئة [Rectangle](../../rectangle/)
* فئة [RectangleF](../../rectanglef/)
* فئة [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* نطاق [System::Drawing](../../)
* Library [Aspose.Slides](../../../)