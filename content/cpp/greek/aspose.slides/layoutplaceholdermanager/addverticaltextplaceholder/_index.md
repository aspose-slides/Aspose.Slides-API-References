---
title: AddVerticalTextPlaceholder()
second_title: Αναφορά API για C++ του Aspose.Slides
description: Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να περιέχει κείμενο σε κατακόρυφη κατεύθυνση.
type: docs
weight: 40
url: /el/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) μέθοδος


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να περιέχει κείμενο σε κατακόρυφη διεύθυνση.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | **float** | Το πλάτος του νέου σχήματος placeholder. |
| height | **float** | Το ύψος του νέου σχήματος placeholder. |

### Τιμή επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με ένα Text (Vertical) placeholder.

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα Text (Vertical) placeholder στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [LayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)