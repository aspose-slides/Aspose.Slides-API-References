---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει το διαχειριστή που διατηρεί τη συμπεριφορά των δεσμευτών θέσης υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας διάταξης διαφάνειας και όλων των θυγατρικών δεσμευτών θέσης. Τα θυγατρικά δεσμευτικά θέσεις σημαίνουν ότι οι δεσμευτές θέσης περιέχονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.
type: docs
weight: 7680
url: /el/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager κλάση

Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

```csharp
public sealed class LayoutSlideHeaderFooterManager : BaseSlideHeaderFooterManager, 
    ILayoutSlideHeaderFooterManager
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsDateTimeVisible](../../aspose.slides/baseslideheaderfootermanager/isdatetimevisible) { get; } | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο κράτησης θέσης ημερομηνίας-ώρας. ReadBoolean. |
| [IsFooterVisible](../../aspose.slides/baseslideheaderfootermanager/isfootervisible) { get; } | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο κράτησης θέσης υποσέλιδου. Read Boolean. |
| [IsSlideNumberVisible](../../aspose.slides/baseslideheaderfootermanager/isslidenumbervisible) { get; } | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο κράτησης θέσης αριθμού σελίδας. ReadBoolean. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetDateTimeAndChildDateTimesText](../../aspose.slides/layoutslideheaderfootermanager/setdatetimeandchilddatetimestext)(string) | Ορίζει κείμενο στο σύμβολο κράτησης θέσης ημερομηνίας-ώρας της διάταξης διαφάνειας και σε όλα τα θυγατρικά σύμβολα κράτησης θέσης ημερομηνίας-ώρας. Τα θυγατρικά σύμβολα κράτησης θέσης σημαίνουν ότι τα σύμβολα κράτησης θέσης περιέχονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| [SetDateTimeAndChildDateTimesVisibility](../../aspose.slides/layoutslideheaderfootermanager/setdatetimeandchilddatetimesvisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης ημερομηνίας-ώρας της διάταξης διαφάνειας και όλων των θυγατρικών συμβόλων κράτησης θέσης ημερομηνίας-ώρας. Τα θυγατρικά σύμβολα κράτησης θέσης σημαίνουν ότι τα σύμβολα κράτησης θέσης περιέχονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| [SetDateTimeText](../../aspose.slides/baseslideheaderfootermanager/setdatetimetext)(string) | Ορίζει κείμενο στο σύμβολο κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας. |
| [SetDateTimeVisibility](../../aspose.slides/baseslideheaderfootermanager/setdatetimevisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας. |
| [SetFooterAndChildFootersText](../../aspose.slides/layoutslideheaderfootermanager/setfooterandchildfooterstext)(string) | Ορίζει κείμενο στο σύμβολο κράτησης θέσης υποσέλιδου της διάταξης διαφάνειας και σε όλα τα θυγατρικά σύμβολα κράτησης θέσης υποσέλιδου. Τα θυγατρικά σύμβολα κράτησης θέσης σημαίνουν ότι τα σύμβολα κράτησης θέσης περιέχονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| [SetFooterAndChildFootersVisibility](../../aspose.slides/layoutslideheaderfootermanager/setfooterandchildfootersvisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης υποσέλιδου της διάταξης διαφάνειας και όλων των θυγατρικών συμβόλων κράτησης θέσης υποσέλιδου. Τα θυγατρικά σύμβολα κράτησης θέσης σημαίνουν ότι τα σύμβολα κράτησης θέσης περιέχονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| [SetFooterText](../../aspose.slides/baseslideheaderfootermanager/setfootertext)(string) | Ορίζει κείμενο στο σύμβολο κράτησης θέσης υποσέλιδου της διαφάνειας. |
| [SetFooterVisibility](../../aspose.slides/baseslideheaderfootermanager/setfootervisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης υποσέλιδου της διαφάνειας. |
| [SetSlideNumberAndChildSlideNumbersVisibility](../../aspose.slides/layoutslideheaderfootermanager/setslidenumberandchildslidenumbersvisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης αριθμού σελίδας της διάταξης διαφάνειας και όλων των θυγατρικών συμβόλων κράτησης θέσης αριθμού σελίδας. Τα θυγατρικά σύμβολα κράτησης θέσης σημαίνουν ότι τα σύμβολα κράτησης θέσης περιέχονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| [SetSlideNumberVisibility](../../aspose.slides/baseslideheaderfootermanager/setslidenumbervisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης αριθμού σελίδας της διαφάνειας. |

### Δείτε επίσης

* κλάση [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager)
* διασύνδεση [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->