---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 參考
description: 返回一個母版投影片的繪圖參考線集合。唯讀 IDrawingGuidesCollection
type: docs
weight: 170
url: /zh-hant/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() 方法

返回一個針對母版投影片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// 在投影片中心右側添加新的垂直繪圖參考線
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 類別 [MasterSlide](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)