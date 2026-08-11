---
title: get_DrawingGuides()
second_title: Aspose.Slides برای مرجع API C++
description: یک مجموعه از راهنمای رسم برای اسلاید چیدمان برمی‌گرداند. فقط خواندنی IDrawingGuidesCollection
type: docs
weight: 79
url: /fa/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() متد


یک مجموعه از راهنمای رسم برای اسلاید چیدمان برمی‌گرداند. فقط خواندنی [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// افزودن راهنمای رسم عمودی جدید به سمت چپ مرکز اسلاید
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDrawingGuidesCollection](../../idrawingguidescollection/)
* کلاس [ILayoutSlide](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)