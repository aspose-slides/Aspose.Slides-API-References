---
title: get_Size()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得線條的筆刷大小（單位：點）。
type: docs
weight: 27
url: /zh-hant/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() 方法


取得線條的筆刷大小（單位：點）。

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
```

## 備註


範例: 
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