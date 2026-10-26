---
title: get_DrawingGuides()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه راهنمای‌های رسم را برمی‌گرداند. فقط خواندنی IDrawingGuidesCollection
type: docs
weight: 53
url: /fa/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() متد

مجموعهٔ راهنمای‌های رسم را برمی‌گرداند. فقط خواندنی [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## ملاحظات

کد نمونهٔ زیر نشان می‌دهد چگونه راهنمای‌های رسم جدید را در یک ارائهٔ PowerPoint اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// افزودن راهنمای رسم عمودی جدید به سمت راست مرکز اسلاید
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// افزودن راهنمای رسم افقی جدید زیر مرکز اسلاید
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDrawingGuidesCollection](../../idrawingguidescollection/)
* کلاس [ICommonSlideViewProperties](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)