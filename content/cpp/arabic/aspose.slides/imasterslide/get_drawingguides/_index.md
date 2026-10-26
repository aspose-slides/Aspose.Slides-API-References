---
title: get_DrawingGuides()
second_title: مرجع API Aspose.Slides للغة C++
description: يرجل مجموعة من خطوط الرسم للعرض الرئيسي. للقراءة فقط IDrawingGuidesCollection
type: docs
weight: 105
url: /ar/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() طريقة


يرجع مجموعة من خطوط الرسم للعرض الرئيسي. للقراءة فقط [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// إضافة دليل الرسم العمودي الجديد إلى يمين مركز الشريحة
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDrawingGuidesCollection](../../idrawingguidescollection/)
* فئة [IMasterSlide](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)