---
title: get_DrawingGuides()
second_title: Aspose.Slides برای مرجع API C++
description: یک مجموعه از راهنمایی‌های رسم را برای اسلاید اصلی برمی‌گرداند. فقط-خواندنی IDrawingGuidesCollection
type: docs
weight: 170
url: /fa/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() متد


یک مجموعه از راهنمایی‌های رسم را برای اسلاید اصلی برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// افزودن راهنمای جدید عمودی به سمت راست مرکز اسلاید
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [MasterSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)