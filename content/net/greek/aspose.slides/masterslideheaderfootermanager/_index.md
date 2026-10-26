---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει διαχειριστή που διατηρεί τη συμπεριφορά των δεσμευτικών θέσεων υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών δεσμευτικών θέσεων. Τα παιδικά δεσμευτικά θέσεων σημαίνουν ότι οι δεσμευτικές θέσεις περιέχονται σε εξαρτώμενες διαφάνειες διάταξης και σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.
type: docs
weight: 8050
url: /el/aspose.slides/masterslideheaderfootermanager/
---
## MasterSlideHeaderFooterManager κλάση

Αντιπροσωπεύει έναν διαχειριστή που κρατά τη συμπεριφορά των δεσμευτικών θέσεων υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών δεσμευτικών θέσεων. Τα παιδικά δεσμευτικά θέσεις σημαίνουν ότι τα σύμβολα βρίσκονται σε διαφάνειες διάταξης και σε διαφάνειες που εξαρτώνται. Οι διαφάνειες διάταξης και οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

```csharp
public sealed class MasterSlideHeaderFooterManager : BaseSlideHeaderFooterManager, 
    IMasterSlideHeaderFooterManager
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
| [SetDateTimeAndChildDateTimesText](../../aspose.slides/masterslideheaderfootermanager/setdatetimeandchilddatetimestext)(string) | Ορίζει κείμενο στο σύμβολο κράτησης θέσης ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλα τα παιδικά σύμβολα κράτησης θέσης ημερομηνίας-ώρας. Τα παιδικά σύμβολα κράτησης θέσης σημαίνουν ότι αυτά τα σύμβολα περιλαμβάνονται σε διαφάνειες διάταξης και σε διαφάνειες που εξαρτώνται. Οι διαφάνειες διάταξης και οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| [SetDateTimeAndChildDateTimesVisibility](../../aspose.slides/masterslideheaderfootermanager/setdatetimeandchilddatetimesvisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των παιδικών συμβόλων κράτησης θέσης ημερομηνίας-ώρας. Τα παιδικά σύμβολα κράτησης θέσης σημαίνουν ότι αυτά τα σύμβολα περιλαμβάνονται σε διαφάνειες διάταξης και σε διαφάνειες που εξαρτώνται. Οι διαφάνειες διάταξης και οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| [SetDateTimeText](../../aspose.slides/baseslideheaderfootermanager/setdatetimetext)(string) | Ορίζει κείμενο στο σύμβολο κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας. |
| [SetDateTimeVisibility](../../aspose.slides/baseslideheaderfootermanager/setdatetimevisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας. |
| [SetFooterAndChildFootersText](../../aspose.slides/masterslideheaderfootermanager/setfooterandchildfooterstext)(string) | Ορίζει κείμενο στο σύμβολο κράτησης θέσης υποσέλιδου της κύριας διαφάνειας και σε όλα τα παιδικά σύμβολα κράτησης θέσης υποσέλιδου. Τα παιδικά σύμβολα κράτησης θέσης σημαίνουν ότι αυτά τα σύμβολα περιλαμβάνονται σε διαφάνειες διάταξης και σε διαφάνειες που εξαρτώνται. Οι διαφάνεις διάταξης και οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| [SetFooterAndChildFootersVisibility](../../aspose.slides/masterslideheaderfootermanager/setfooterandchildfootersvisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης υποσέλιδου της κύριας διαφάνειας και όλων των παιδικών συμβόλων κράτησης θέσης υποσέλιδου. Τα παιδικά σύμβολα κράτησης θέσης σημαίνουν ότι αυτά τα σύμβολα περιλαμβάνονται σε διαφάνειες διάταξης και σε διαφάνειες που εξαρτώνται. Οι διαφάνειες διάταξης και οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| [SetFooterText](../../aspose.slides/baseslideheaderfootermanager/setfootertext)(string) | Ορίζει κείμενο στο σύμβολο κράτησης θέσης υποσέλιδου της διαφάνειας. |
| [SetFooterVisibility](../../aspose.slides/baseslideheaderfootermanager/setfootervisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης υποσέλιδου της διαφάνειας. |
| [SetSlideNumberAndChildSlideNumbersVisibility](../../aspose.slides/masterslideheaderfootermanager/setslidenumberandchildslidenumbersvisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών συμβόλων κράτησης θέσης αριθμού σελίδας. Τα παιδικά σύμβολα κράτησης θέσης σημαίνουν ότι αυτά τα σύμβολα περιλαμβάνονται σε διαφάνειες διάταξης και σε διαφάνειες που εξαρτώνται. Οι διαφάνειες διάταξης και οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια. |
| [SetSlideNumberVisibility](../../aspose.slides/baseslideheaderfootermanager/setslidenumbervisibility)(bool) | Αλλάζει την ορατότητα του συμβόλου κράτησης θέσης αριθμού σελίδας της διαφάνειας. |

### Δείτε επίσης

* κλάση [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager)
* διεπαφή [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->