---
title: get_DrawingGuides()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για τη διαφάνεια διάταξης. Μόνο για ανάγνωση IDrawingGuidesCollection
type: docs
weight: 118
url: /el/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() μέθοδος

Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για τη διαφάνεια διάταξης. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Προσθήκη της νέας κατακόρυφης οδηγίας σχεδίασης στα αριστερά του κέντρου της διαφάνειας
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Κλάση [LayoutSlide](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)