---
title: get_DrawingGuides()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια κύριας σημειώσεων. Μόνο για ανάγνωση IDrawingGuidesCollection
type: docs
weight: 53
url: /el/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() μέθοδος


Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια κύριας σημειώσεων. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Κλάση [MasterHandoutSlide](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)