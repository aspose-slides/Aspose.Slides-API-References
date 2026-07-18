---
title: get_DrawingGuides()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια διάταξης. Μόνο ανάγνωση IDrawingGuidesCollection
type: docs
weight: 79
url: /el/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() μέθοδος

Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια διάταξης. Μόνο ανάγνωση [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Προσθήκη του νέου κάθετου οδηγού σχεδίασης στα αριστερά του κέντρου της διαφάνειας
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Κλάση [ILayoutSlide](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)