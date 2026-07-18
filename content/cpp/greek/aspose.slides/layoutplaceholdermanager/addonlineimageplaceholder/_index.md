---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα νέο σχήμα σύμβολο κράτησης θέσης στη διαφάνεια διάταξης για τη διατήρηση μιας διαδικτυακής εικόνας.
type: docs
weight: 118
url: /el/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) μέθοδος

Προσθέτει ένα νέο σχήμα σύμβολο κράτησης θέσης διαδικτυακής εικόνας στη διαφάνεια διάταξης.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη X του νέου σχήματος σύμβολο κράτησης θέσης διαδικτυακής εικόνας. |
| y | **float** | Η συντεταγμένη Y του νέου σχήματος σύμβολο κράτησης θέσης διαδικτυακής εικόνας. |
| width | **float** | Το πλάτος του νέου σχήματος σύμβολο κράτησης θέσης διαδικτυακής εικόνας. |
| height | **float** | Το ύψος του νέου σχήματος σύμβολο κράτησης θέσης διαδικτυακής εικόνας. |

### Τιμή Επιστροφής

Δημιουργήθηκε [IAutoShape](../../iautoshape/) με σύμβολο κράτησης θέσης διαδικτυακής εικόνας.

## Παρατηρήσεις

Το ακόλουθο παράδειγμα δείχνει πώς να προσθέσετε το σχήμα σύμβολο κράτησης θέσης διαδικτυακής εικόνας στη διαφάνεια διάταξης.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [LayoutPlaceholderManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)