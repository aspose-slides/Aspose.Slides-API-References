---
title: get_DrawingGuides()
second_title: Aspose.Slides for C++ API Referansı
description: Ana not slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur IDrawingGuidesCollection
type: docs
weight: 27
url: /tr/aspose.slides/imasternotesslide/get_drawingguides/
---
## IMasterNotesSlide::get_DrawingGuides() metodu

Ana not slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterNotesSlide::get_DrawingGuides()=0
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

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Sınıf [IMasterNotesSlide](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)