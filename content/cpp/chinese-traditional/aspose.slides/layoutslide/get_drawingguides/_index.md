---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 參考
description: 傳回佈局投影片的繪圖參考線集合。唯讀 IDrawingGuidesCollection
type: docs
weight: 118
url: /zh-hant/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() 方法


傳回佈局投影片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// 在投影片中心左側新增垂直繪圖參考線
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 類別 [LayoutSlide](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)