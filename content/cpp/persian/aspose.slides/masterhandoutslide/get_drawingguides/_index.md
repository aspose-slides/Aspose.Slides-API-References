---
title: get_DrawingGuides()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی هندآوت را برمی‌گرداند. فقط-خواندنی IDrawingGuidesCollection
type: docs
weight: 53
url: /fa/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() متد


مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی هندآوت را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDrawingGuidesCollection](../../idrawingguidescollection/)
* کلاس [MasterHandoutSlide](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)