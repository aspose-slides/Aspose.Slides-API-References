---
title: get_DrawingGuides()
second_title: Aspose.Slides برای مرجع API C++
description: مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی را برمی‌گرداند. فقط خواندنی IDrawingGuidesCollection
type: docs
weight: 105
url: /fa/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() متد

یک مجموعه از راهنمایی‌های رسم برای اسلاید اصلی باز می‌گرداند. فقط خواندنی [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## توضیحات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// افزودن راهنمای رسم عمودی جدید به سمت راست مرکز اسلاید
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDrawingGuidesCollection](../../idrawingguidescollection/)
* کلاس [IMasterSlide](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)