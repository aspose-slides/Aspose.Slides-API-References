---
title: AddContentPlaceholder()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να περιέχει περιεχόμενο, όπως εικόνα, πίνακας, πολυμέσα ή κείμενο.
type: docs
weight: 1
url: /el/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) μέθοδος

Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για να περιέχει περιεχόμενο, όπως εικόνα, πίνακας, πολυμέσα ή κείμενο.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος κράτησης θέσης. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος κράτησης θέσης. |
| width | **float** | Το πλάτος του νέου σχήματος κράτησης θέσης. |
| height | **float** | Το ύψος του νέου σχήματος κράτησης θέσης. |

### Return Value

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με ένα placeholder Περιεχομένου.

## Remarks

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα placeholder Περιεχομένου στη διαφάνεια διάταξης.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [LayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)