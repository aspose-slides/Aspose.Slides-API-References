---
title: get_SlideSize()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Μόνο για ανάγνωση ISlideSize.
type: docs
weight: 79
url: /el/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() μέθοδος

Επιστρέφει το αντικείμενο μεγέθους διαφάνειας. Μόνο για ανάγνωση [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να αλλάξετε το μέγεθος της διαφάνειας σε ένα PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε το μέγεθος της διαφάνειας σε σχέση με την κλιμάκωση του περιεχομένου για ένα PowerPoint [Presentation](../). 
```cpp
// Δημιουργία ενός αντικειμένου Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Ορισμός του μεγέθους διαφάνειας των παραγόμενων παρουσιάσεων στο ίδιο με το πηγαίο
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Η μέθοδος SetSize χρησιμοποιείται για ορισμό του μεγέθους διαφάνειας με κλιμάκωση του περιεχομένου ώστε να ταιριάζει
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Η μέθοδος SetSize χρησιμοποιείται για ορισμό του μεγέθους διαφάνειας με μεγιστοποίηση του μεγέθους του περιεχομένου
// Αποθήκευση της Presentation στο δίσκο
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
Το παρακάτω παράδειγμα δείχνει πώς να καθορίσετε προσαρμοσμένα μεγέθη διαφάνειας σε ένα PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Μέγεθος χαρτιού A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlideSize](../../islidesize/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)