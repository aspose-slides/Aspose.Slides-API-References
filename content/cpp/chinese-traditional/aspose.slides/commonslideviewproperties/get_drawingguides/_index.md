---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回繪圖參考線的集合。唯讀 IDrawingGuidesCollection
type: docs
weight: 53
url: /zh-hant/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() 方法

返回繪圖參考線的集合。唯讀 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## 備註

以下範例程式碼說明了如何在 PowerPoint 簡報中新增繪圖參考線。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// 將新的垂直繪圖參考線加入至投影片中心右側
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// 將新的水平繪圖參考線加入至投影片中心下方
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 類別 [CommonSlideViewProperties](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)