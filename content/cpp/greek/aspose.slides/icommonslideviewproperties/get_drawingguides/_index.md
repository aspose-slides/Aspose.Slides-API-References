---
title: get_DrawingGuides()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει τη συλλογή των οδηγών σχεδίασης. Μόνο για ανάγνωση IDrawingGuidesCollection
type: docs
weight: 53
url: /el/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() μέθοδος

Επιστρέφει τη συλλογή των οδηγών σχεδίασης. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Σχόλια

Ο παρακάτω κώδικας δείγματος δείχνει πώς να προσθέσετε τους νέους οδηγούς σχεδίασης σε μια παρουσίαση PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Προσθήκη του νέου κάθετου οδηγού σχεδίασης δεξιά του κέντρου της διαφάνειας
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Προσθήκη του νέου οριζόντιου οδηγού σχεδίασης κάτω από το κέντρο της διαφάνειας
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [ICommonSlideViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)