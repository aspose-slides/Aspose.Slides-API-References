---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回主備註投影片的繪圖參考線集合。唯讀 IDrawingGuidesCollection
type: docs
weight: 27
url: /zh-hant/aspose.slides/imasternotesslide/get_drawingguides/
---
## IMasterNotesSlide::get_DrawingGuides() 方法

傳回主備註投影片的繪圖參考線集合。唯讀 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterNotesSlide::get_DrawingGuides()=0
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 類別 [IMasterNotesSlide](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)