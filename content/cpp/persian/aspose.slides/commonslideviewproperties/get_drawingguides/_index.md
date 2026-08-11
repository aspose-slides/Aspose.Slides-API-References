---
title: get_DrawingGuides()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعهٔ راهنماهای رسم را برمی‌گرداند. فقط-خواندنی IDrawingGuidesCollection
type: docs
weight: 53
url: /fa/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() متد

مجموعهٔ راهنماهای رسم را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## ملاحظات

کد نمونهٔ زیر نشان می‌دهد چگونه راهنماهای رسم جدید را در یک ارائهٔ PowerPoint اضافه کنیم. ```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// افزودن راهنمای رسم عمودی جدید به سمت راست مرکز اسلاید
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// افزودن راهنمای رسم افقی جدید به زیر مرکز اسلاید
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IDrawingGuidesCollection](../../idrawingguidescollection/)
* کلاس [CommonSlideViewProperties](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)