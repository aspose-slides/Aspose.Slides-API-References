---
title: get_Brush()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得 IInkLine IInkBrush 的 Brush，唯讀。
type: docs
weight: 1
url: /zh-hant/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() 方法


取得 IInkLine [IInkBrush](../../iinkbrush/) 的 Brush，唯讀。

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IInkBrush](../../iinkbrush/)
* 類別 [IInkTrace](../)
* 命名空間 [Aspose::Slides::Ink](../../)
* 函式庫 [Aspose.Slides](../../../)