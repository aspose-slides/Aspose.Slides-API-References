---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API 参考
description: 返回用于主备注幻灯片的绘图参考线集合。只读 IDrawingGuidesCollection
type: docs
weight: 66
url: /zh/aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() 方法


返回一个用于主备注幻灯片的绘图参考线集合。只读 [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
```

## 备注



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDrawingGuidesCollection](../../idrawingguidescollection/)
* 类 [MasterNotesSlide](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)