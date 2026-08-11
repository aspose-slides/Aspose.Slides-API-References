---
title: get_DrawingGuides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إرجاع مجموعة من أدلة الرسم للشرائح التخطيطية. للقراءة فقط IDrawingGuidesCollection
type: docs
weight: 118
url: /ar/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() طريقة

إرجاع مجموعة من أدلة الرسم للشرائح التخطيطية. للقراءة فقط [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// إضافة دليل الرسم العمودي الجديد إلى يسار مركز الشريحة
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDrawingGuidesCollection](../../idrawingguidescollection/)
* فئة [LayoutSlide](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)