---
title: get_Size()
second_title: Aspose.Slides for C++ API 参考
description: 获取线条的笔刷大小（单位为点）。
type: docs
weight: 27
url: /zh/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() 方法


获取线条的笔刷大小（单位为点）。

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## 备注


示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## 另见

* 类 [SizeF](../../../system.drawing/sizef/)
* 类 [InkBrush](../)
* 命名空间 [Aspose::Slides::Ink](../../)
* 库 [Aspose.Slides](../../../)