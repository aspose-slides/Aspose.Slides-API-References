---
title: AddChartPlaceholder()
second_title: Aspose.Slides για την αναφορά API C++
description: Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για να φιλοξενήσει ένα γράφημα.
type: docs
weight: 66
url: /el/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) μέθοδος

Προσθέτει ένα νέο σχήμα κράτησης θέσης στη διαφάνεια διάταξης για να φιλοξενήσει ένα γράφημα.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος κράτησης θέσης. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος κράτησης θέσης. |
| width | **float** | Το πλάτος του νέου σχήματος κράτησης θέσης. |
| height | **float** | Το ύψος του νέου σχήματος κράτησης θέσης. |

### Τιμή Επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με μια Chart placeholder.

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα Chart placeholder στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [LayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)