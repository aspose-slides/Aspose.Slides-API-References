---
title: set_Color()
second_title: Aspose.Slides for C++ API 参考
description: 设置线条的画笔颜色。
type: docs
weight: 14
url: /zh/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) 方法

设置线条的画笔颜色。

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## 另见

* 类 [Color](../../../system.drawing/color/)
* 类 [IInkBrush](../)
* 命名空间 [Aspose::Slides::Ink](../../)
* 库 [Aspose.Slides](../../../)