---
title: get_DrawingGuides()
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعه‌ای از راهنمایی‌های رسم را برای اسلاید خلاصه اصلی برمی‌گرداند. فقط-خواندنی IDrawingGuidesCollection
type: docs
weight: 14
url: /fa/aspose.slides/imasterhandoutslide/get_drawingguides/
---
## IMasterHandoutSlide::get_DrawingGuides() متد

مجموعه‌ای از راهنمایی‌های رسم را برای اسلاید خلاصه اصلی برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterHandoutSlide::get_DrawingGuides()=0
```

## توضیحات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// اضافه کردن راهنمای رسم افقی جدید بالای مرکز اسلاید
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDrawingGuidesCollection](../../idrawingguidescollection/)
* کلاس [IMasterHandoutSlide](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)