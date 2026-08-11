---
title: get_DrawingGuides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع مجموعة من إرشادات الرسم لشريحة التخطيط. للقراءة فقط IDrawingGuidesCollection
type: docs
weight: 79
url: /ar/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() طريقة


يرجع مجموعة من إرشادات الرسم لشريحة التخطيط. للقراءة فقط [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
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
* فئة [ILayoutSlide](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)