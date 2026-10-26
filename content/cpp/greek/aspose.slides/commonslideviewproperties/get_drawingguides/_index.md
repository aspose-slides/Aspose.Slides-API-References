---
title: get_DrawingGuides()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει τη συλλογή των οδηγών σχεδίασης. Μόνο για ανάγνωση IDrawingGuidesCollection
type: docs
weight: 53
url: /el/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() μέθοδος


Επιστρέφει τη συλλογή των οδηγών σχεδίασης. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Παρατηρήσεις


Ο παρακάτω κώδικας δείγματος δείχνει πώς να προσθέσετε τους νέους οδηγούς σχεδίασης σε μια παρουσίαση PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Προσθήκη του νέου κάθετου οδηγού σχεδίασης στα δεξιά του κέντρου της διαφάνειας
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Προσθήκη του νέου οριζόντιου οδηγού σχεδίασης κάτω από το κέντρο της διαφάνειας
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Κλάση [CommonSlideViewProperties](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)