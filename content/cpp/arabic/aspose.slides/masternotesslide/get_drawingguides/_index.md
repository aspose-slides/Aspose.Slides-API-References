---
title: get_DrawingGuides()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إرجاع مجموعة من خطوط الرسم لشريحة الملاحظات الرئيسية. للقراءة فقط IDrawingGuidesCollection
type: docs
weight: 66
url: /ar/aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() طريقة

يرجع مجموعة من خطوط الرسم لشريحة الملاحظات الرئيسية. للقراءة فقط [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDrawingGuidesCollection](../../idrawingguidescollection/)
* فئة [MasterNotesSlide](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)