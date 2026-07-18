---
title: AddTablePlaceholder()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει έναν πίνακα.
type: docs
weight: 79
url: /el/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) μέθοδος

Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει έναν πίνακα.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | **float** | Το πλάτος του νέου σχήματος placeholder. |
| height | **float** | Το ύψος του νέου σχήματος placeholder. |

### Τιμή επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με ένα [Table](../../table/) placeholder.

## Παρατηρήσεις

Το ακόλουθο παράδειγμα δείχνει πώς να προσθέσετε το σχήμα [Table](../../table/) placeholder στη διαφάνεια διάταξης. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [ILayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)