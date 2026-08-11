---
title: get_DrawingGuides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع مجموعة من إرشادات الرسم لشريحة المخططات الرئيسية. للقراءة فقط IDrawingGuidesCollection
type: docs
weight: 53
url: /ar/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() طريقة

تُرجِع مجموعة من إرشادات الرسم لشريحة المخططات الرئيسية. للقراءة فقط [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDrawingGuidesCollection](../../idrawingguidescollection/)
* فئة [MasterHandoutSlide](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)