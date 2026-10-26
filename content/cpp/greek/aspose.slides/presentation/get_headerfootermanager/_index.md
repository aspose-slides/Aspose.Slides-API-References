---
title: get_HeaderFooterManager()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει τον τρέχοντα διαχειριστή HeaderFooter. Μόνο-ανάγνωση IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /el/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() μέθοδος


Επιστρέφει τον τρέχοντα διαχειριστή HeaderFooter. Μόνο-ανάγνωση [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Παρατηρήσεις


Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε την ορατότητα του υποσέλιδου μέσα στο [Slide](../../slide/) του PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Η ιδιότητα IsFooterVisible χρησιμοποιείται για να υποδείξει ότι ο placeholder υποσέλιδου της διαφάνειας δεν υπάρχει.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Η μέθοδος SetFooterVisibility χρησιμοποιείται για να κάνει ορατό τον placeholder υποσέλιδου της διαφάνειας.
    headerFooterManager->SetFooterVisibility(true);
}

// Η ιδιότητα IsSlideNumberVisible χρησιμοποιείται για να υποδείξει ότι ο placeholder αριθμού σελίδας της διαφάνειας δεν υπάρχει.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Η μέθοδος SetSlideNumberVisibility χρησιμοποιείται για να κάνει ορατό τον placeholder αριθμού σελίδας της διαφάνειας.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Η ιδιότητα IsDateTimeVisible χρησιμοποιείται για να υποδείξει ότι ο placeholder ημερομηνίας-ώρας της διαφάνειας δεν υπάρχει.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Η μέθοδος SetFooterVisibility χρησιμοποιείται για να κάνει ορατό τον placeholder ημερομηνίας-ώρας της διαφάνειας.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Η μέθοδος SetFooterText χρησιμοποιείται για να ορίσει κείμενο στον placeholder υποσέλιδου της διαφάνειας.
headerFooterManager->SetFooterText(u"Footer text");
// Η μέθοδος SetDateTimeText χρησιμοποιείται για να ορίσει κείμενο στον placeholder ημερομηνίας-ώρας της διαφάνειας.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε την ορατότητα του υποσέλιδου παιδιού μέσα στο [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Η μέθοδος SetFooterAndChildFootersVisibility χρησιμοποιείται για την ενεργοποίηση ορατότητας μιας κύριας διαφάνειας και όλων των child placeholder υποσέλιδου.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Η μέθοδος SetSlideNumberAndChildSlideNumbersVisibility χρησιμοποιείται για την ενεργοποίηση ορατότητας μιας κύριας διαφάνειας και όλων των child placeholder αριθμού σελίδας.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Η μέθοδος SetDateTimeAndChildDateTimesVisibility χρησιμοποιείται για την ενεργοποίηση ορατότητας μιας κύριας διαφάνειας και όλων των child placeholder ημερομηνίας-ώρας.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Η μέθοδος SetFooterAndChildFootersText χρησιμοποιείται για τον ορισμό κειμένου σε μια κύρια διαφάνεια και όλα τα child placeholder υποσέλιδου.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Η μέθοδος SetDateTimeAndChildDateTimesText χρησιμοποιείται για τον ορισμό κειμένου σε μια κύρια διαφάνεια και όλα τα child placeholder ημερομηνίας-ώρας.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)