---
title: get_DrawingGuides()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: تُرجِع مجموعة من إرشادات الرسم للماستر سلايد. للقراءة فقط IDrawingGuidesCollection
type: docs
weight: 170
url: /ar/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() method

إرجاع مجموعة من إرشادات الرسم للماستر سلايد. للقراءة فقط [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
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

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDrawingGuidesCollection](../../idrawingguidescollection/)
* فئة [MasterSlide](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)