---
title: get_DrawingGuides()
second_title: Aspose.Slides için C++ API Referansı
description: Ana not slaytı için bir çizim kılavuzu koleksiyonu döndürür. Salt okuma IDrawingGuidesCollection
type: docs
weight: 66
url: /tr/aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() metodu

Ana not slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okuma [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Sınıf [MasterNotesSlide](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)