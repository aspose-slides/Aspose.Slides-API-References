---
title: set_Size()
second_title: Aspose.Slides for C++ API 參考
description: 設定線條的筆刷大小（以點為單位）。
type: docs
weight: 40
url: /zh-hant/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) 方法


設定線條的筆刷大小（以點為單位）。

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## 另請參閱

* 類別 [SizeF](../../../system.drawing/sizef/)
* 類別 [IInkBrush](../)
* 命名空間 [Aspose::Slides::Ink](../../)
* 函式庫 [Aspose.Slides](../../../)