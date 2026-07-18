---
title: AddTablePlaceholder()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα νέο σχήμα κράτησης στο layout slide για να φιλοξενήσει έναν πίνακα.
type: docs
weight: 79
url: /el/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) μέθοδος

Προσθέτει ένα νέο σχήμα κράτησης στο layout slide για να φιλοξενήσει έναν πίνακα.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος κράτησης. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος κράτησης. |
| width | **float** | Το πλάτος του νέου σχήματος κράτησης. |
| height | **float** | Το ύψος του νέου σχήματος κράτησης. |

### Τιμή Επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με ένα [Table](../../table/) σύμβολο κράτησης.

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα [Table](../../table/) placeholder στο layout slide. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)