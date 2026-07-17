---
title: get_Color()
second_title: Aspose.Slides for C++ API 参考
description: 获取线条的笔刷颜色。
type: docs
weight: 1
url: /zh/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() 方法

获取线条的笔刷颜色。

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
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