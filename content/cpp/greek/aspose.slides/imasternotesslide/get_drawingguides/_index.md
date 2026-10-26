---
title: get_DrawingGuides()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια master notes. Μόνο για ανάγνωση IDrawingGuidesCollection
type: docs
weight: 27
url: /el/aspose.slides/imasternotesslide/get_drawingguides/
---
## IMasterNotesSlide::get_DrawingGuides() method

Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια master notes. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterNotesSlide::get_DrawingGuides()=0
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Κλάση [IMasterNotesSlide](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)