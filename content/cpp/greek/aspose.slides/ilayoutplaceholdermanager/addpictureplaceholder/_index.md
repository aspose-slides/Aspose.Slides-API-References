---
title: AddPicturePlaceholder()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για να φιλοξενήσει μια εικόνα.
type: docs
weight: 53
url: /el/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) μέθοδος

Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για την προσθήκη μιας εικόνας.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος κράτησης θέσης. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος κράτησης θέσης. |
| width | **float** | Το πλάτος του νέου σχήματος κράτησης θέσης. |
| height | **float** | Το ύψος του νέου σχήματος κράτησης θέσης. |

### Τιμή επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με μια [Picture](../../picture/) κράτηση θέσης.
## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα [Picture](../../picture/) κράτησης θέσης στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [ILayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)