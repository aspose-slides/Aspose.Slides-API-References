---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回 master handout slide 的繪圖參考線集合。唯讀 IDrawingGuidesCollection
type: docs
weight: 53
url: /zh-hant/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() 方法


返回 master handout slide 的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 類別 [MasterHandoutSlide](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)