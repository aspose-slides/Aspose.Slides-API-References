---
title: get_Color()
second_title: Aspose.Slides for C++ API 參考
description: 取得線條的筆刷顏色。
type: docs
weight: 1
url: /zh-hant/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() 方法


取得線條的筆刷顏色。

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## 另見

* 類別 [Color](../../../system.drawing/color/)
* 類別 [IInkBrush](../)
* 命名空間 [Aspose::Slides::Ink](../../)
* 函式庫 [Aspose.Slides](../../../)