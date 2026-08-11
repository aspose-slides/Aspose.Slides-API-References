---
title: get_DrawingGuides()
second_title: مرجع API Aspose.Slides برای C++
description: یک مجموعه از راهنماهای رسم برای اسلاید طرح برمی‌گرداند. فقط-خواندنی IDrawingGuidesCollection
type: docs
weight: 118
url: /fa/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() متد

یک مجموعه از راهنماهای رسم برای اسلاید طرح برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// اضافه کردن راهنمای رسم عمودی جدید به سمت چپ مرکز اسلاید
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IDrawingGuidesCollection](../../idrawingguidescollection/)
* کلاس [LayoutSlide](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)