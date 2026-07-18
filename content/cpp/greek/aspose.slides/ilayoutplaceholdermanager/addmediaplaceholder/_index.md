---
title: AddMediaPlaceholder()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσθέτει ένα νέο σχήμα κράτησης στη διαφάνεια διάταξης για να φιλοξενήσει ένα αντικείμενο πολυμέσων.
type: docs
weight: 105
url: /el/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) μέθοδος

Προσθέτει ένα νέο σχήμα κράτησης στη διαφάνεια διάταξης για να φιλοξενήσει ένα αντικείμενο πολυμέσων.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος κράτησης. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος κράτησης. |
| width | **float** | Το πλάτος του νέου σχήματος κράτησης. |
| height | **float** | Το ύψος του νέου σχήματος κράτησης. |

### Τιμή Επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με ένα Media placeholder.

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα Media placeholder στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [ILayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)