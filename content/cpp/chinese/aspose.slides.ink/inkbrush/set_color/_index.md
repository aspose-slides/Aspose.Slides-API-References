---
title: set_Color()
second_title: Aspose.Slides for C++ API 参考
description: 设置线条的画笔颜色。
type: docs
weight: 14
url: /zh/aspose.slides.ink/inkbrush/set_color/
---
## InkBrush::set_Color(System::Drawing::Color) 方法


设置线条的画笔颜色。

```cpp
void Aspose::Slides::Ink::InkBrush::set_Color(System::Drawing::Color value) override
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

## 另请参见

* 类 [Color](../../../system.drawing/color/)
* 类 [InkBrush](../)
* 命名空间 [Aspose::Slides::Ink](../../)
* 库 [Aspose.Slides](../../../)