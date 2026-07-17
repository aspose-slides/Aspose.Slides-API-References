---
title: get_Points()
second_title: Aspose.Slides C++ API 参考
description: "获取 IInkLine System::Drawing::PointF 的点，只读."
type: docs
weight: 14
url: /zh/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() 方法

获取 IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) 的点，只读。

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [IInkTrace](../)
* 命名空间 [Aspose::Slides::Ink](../../)
* 库 [Aspose.Slides](../../../)