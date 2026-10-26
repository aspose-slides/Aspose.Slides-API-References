---
title: AddSmartArtPlaceholder()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για να φιλοξενήσει ένα διάγραμμα SmartArt.
type: docs
weight: 92
url: /el/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) μέθοδος


Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για να φιλοξενήσει ένα διάγραμμα [SmartArt](../../../aspose.slides.smartart/).

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X coordinate of the new placeholder shape. |
| y | **float** | The Y coordinate of the new placeholder shape. |
| width | **float** | The width of the new placeholder shape. |
| height | **float** | The height of the new placeholder shape. |

### Τιμή επιστροφής

Created [IAutoShape](../../iautoshape/) with a [SmartArt](../../../aspose.slides.smartart/) placeholder.
## Σχόλια



Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα κράτησης θέσης [SmartArt](../../../aspose.slides.smartart/) στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [ILayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)