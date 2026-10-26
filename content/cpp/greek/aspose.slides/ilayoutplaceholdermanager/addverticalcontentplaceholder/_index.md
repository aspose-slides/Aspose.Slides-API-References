---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για να περιέχει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσα ή κείμενο σε κατακόρυφη κατεύθυνση.
type: docs
weight: 14
url: /el/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) μέθοδος

Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσα ή κείμενο σε κατακόρυφη κατεύθυνση.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος κράτησης θέσης. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος κράτησης θέσης. |
| width | **float** | Το πλάτος του νέου σχήματος κράτησης θέσης. |
| height | **float** | Το ύψος του νέου σχήματος κράτησης θέσης. |

### Τιμή Επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με μια κράτηση θέσης Περιεχομένου (Κατακόρυφο).

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα κράτησης θέσης Περιεχομένου (Κατακόρυφο) στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [ILayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)