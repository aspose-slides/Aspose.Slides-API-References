---
title: IMasterSlideHeaderFooterManager
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των δεσμευτικών θέσεων υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών θέσεων.
type: docs
url: /el/com.aspose.slides/imasterslideheaderfootermanager/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των δεσμευτικών θέσεων υποσέλιδου κύριας διαφάνειας, ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών δεσμευτικών θέσεων. Οι θυγατρικές δεσμευτικές θέσεις σημαίνουν ότι οι δεσμευτικές θέσεις περιέχονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα της δεσμευτικής θέσης υποσέλιδου της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών θέσεων υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα της δεσμευτικής θέσης αριθμού σελίδας της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών θέσεων αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα της δεσμευτικής θέσης ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών θέσεων ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στη δεσμευτική θέση υποσέλιδου της κύριας διαφάνειας και σε όλες τις θυγατρικές δεσμευτικές θέσεις υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στη δεσμευτική θέση ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλες τις θυγατρικές δεσμευτικές θέσεις ημερομηνίας-ώρας. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Αλλάζει την ορατότητα της δεσμευτικής θέσης υποσέλιδου της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών θέσεων υποσέλιδου. Οι θυγατρικές δεσμευτικές θέσεις σημαίνουν ότι οι δεσμευτικές θέσεις περιέχονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τις δεσμευτικές θέσεις υποσέλιδου ορατές, αλλιώς - τις κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Αλλάζει την ορατότητα της δεσμευτικής θέσης αριθμού σελίδας της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών θέσεων αριθμού σελίδας. Οι θυγατρικές δεσμευτικές θέσεις σημαίνουν ότι οι δεσμευτικές θέσεις περιέχονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τις δεσμευτικές θέσεις αριθμού σελίδας ορατές, αλλιώς - τις κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Αλλάζει την ορατότητα της δεσμευτικής θέσης ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των θυγατρικών δεσμευτικών θέσεων ημερομηνίας-ώρας. Οι θυγατρικές δεσμευτικές θέσεις σημαίνουν ότι οι δεσμευτικές θέσεις περιέχονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τις δεσμευτικές θέσεις ημερομηνίας-ώρας ορατές, αλλιώς - τις κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Ορίζει κείμενο στη δεσμευτική θέση υποσέλιδου της κύριας διαφάνειας και σε όλες τις θυγατρικές δεσμευτικές θέσεις υποσέλιδου. Οι θυγατρικές δεσμευτικές θέσεις σημαίνουν ότι οι δεσμευτικές θέσεις περιέχονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Ορίζει κείμενο στη δεσμευτική θέση ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλες τις θυγατρικές δεσμευτικές θέσεις ημερομηνίας-ώρας. Οι θυγατρικές δεσμευτικές θέσεις σημαίνουν ότι οι δεσμευτικές θέσεις περιέχονται σε εξαρτώμενες διαφάνειες διάταξης και εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |