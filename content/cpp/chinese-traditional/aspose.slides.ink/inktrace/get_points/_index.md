---
title: get_Points()
second_title: Aspose.Slides for C++ API 參考文件
description: "取得 IInkLine System::Drawing::PointF 的點，唯讀。"
type: docs
weight: 14
url: /zh-hant/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() 方法


取得 IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) 的點，唯讀。

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## 備註


範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## 另見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [InkTrace](../)
* 命名空間 [Aspose::Slides::Ink](../../)
* 函式庫 [Aspose.Slides](../../../)