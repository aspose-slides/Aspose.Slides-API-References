---
title: AddMediaPlaceholder()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να φιλοξενήσει ένα αντικείμενο media.
type: docs
weight: 105
url: /el/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) μέθοδος

Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει ένα αντικείμενο media.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | **float** | Το πλάτος του νέου σχήματος placeholder. |
| height | **float** | Το ύψος του νέου σχήματος placeholder. |

### Τιμή Επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με ένα Media placeholder.

## Σχόλια

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα Media placeholder στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [LayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)