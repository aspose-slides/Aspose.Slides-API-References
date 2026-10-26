---
title: get_DrawingGuides()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη κύρια διαφάνεια. Μόνο για ανάγνωση IDrawingGuidesCollection
type: docs
weight: 170
url: /el/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() μέθοδος


Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη κύρια διαφάνεια. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Σχόλια


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Προσθήκη του νέου κατακόρυφου οδηγού σχεδίασης δεξιά από το κέντρο της διαφάνειας
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Κλάση [MasterSlide](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)