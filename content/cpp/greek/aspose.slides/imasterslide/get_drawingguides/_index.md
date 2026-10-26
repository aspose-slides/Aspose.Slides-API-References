---
title: get_DrawingGuides()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη κύρια διαφάνεια. Μόνο για ανάγνωση IDrawingGuidesCollection
type: docs
weight: 105
url: /el/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() μέθοδος


Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη κύρια διαφάνεια. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Προσθήκη του νέου κατακόρυφου οδηγού σχεδίασης δεξιά του κέντρου της διαφάνειας
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Κλάση [IMasterSlide](../)
* Ονομαστικός χώρος [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)