---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides για Java API Reference
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των δεσμευτικών σημείων υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας της διάταξης διαφάνειας, καθώς και όλων των θυγατρικών δεσμευτικών σημείων.
type: docs
url: /el/com.aspose.slides/layoutslideheaderfootermanager/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των δεσμευτικών σημείων υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας της διάταξης διαφάνειας καθώς και όλων των θυγατρικών δεσμευτικών σημείων. Τα θυγατρικά δεσμευτικά σημεία σημαίνουν ότι τα δεσμευτικά σημεία περιλαμβάνονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του δεσμευτικού σημείου υποσέλιδου της διαφάνειας διάταξης και όλων των θυγατρικών δεσμευτικών σημείων υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του δεσμευτικού σημείου αριθμού σελίδας της διαφάνειας διάταξης και όλων των θυγατρικών δεσμευτικών σημείων αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του δεσμευτικού σημείου ημερομηνίας-ώρας της διαφάνειας διάταξης και όλων των θυγατρικών δεσμευτικών σημείων ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο δεσμευτικό σημείο υποσέλιδου της διαφάνειας διάταξης και σε όλα τα θυγατρικά δεσμευτικά σημεία υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στο δεσμευτικό σημείο ημερομηνίας-ώρας της διαφάνειας διάταξης και σε όλα τα θυγατρικά δεσμευτικά σημεία ημερομηνίας-ώρας. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του δεσμευτικού σημείου υποσέλιδου της διαφάνειας διάταξης και όλων των θυγατρικών δεσμευτικών σημείων υποσέλιδου. Τα θυγατρικά δεσμευτικά σημεία σημαίνουν ότι τα δεσμευτικά σημεία περιλαμβάνονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη μητρική διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα δεσμευτικά σημεία υποσέλιδου ορατά, διαφορετικά τα κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του δεσμευτικού σημείου αριθμού σελίδας της διαφάνειας διάταξης και όλων των θυγατρικών δεσμευτικών σημείων αριθμού σελίδας. Τα θυγατρικά δεσμευτικά σημεία σημαίνουν ότι τα δεσμευτικά σημεία περιλαμβάνονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα δεσμευτικά σημεία αριθμού σελίδας ορατά, διαφορετικά τα κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του δεσμευτικού σημείου ημερομηνίας-ώρας της διαφάνειας διάταξης και όλων των θυγατρικών δεσμευτικών σημείων ημερομηνίας-ώρας. Τα θυγατρικά δεσμευτικά σημεία σημαίνουν ότι τα δεσμευτικά σημεία περιλαμβάνονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα δεσμευτικά σημεία ημερομηνίας-ώρας ορατά, διαφορετικά τα κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στο δεσμευτικό σημείο υποσέλιδου της διαφάνειας διάταξης και σε όλα τα θυγατρικά δεσμευτικά σημεία υποσέλιδου. Τα θυγατρικά δεσμευτικά σημεία σημαίνουν ότι τα δεσμευτικά σημεία περιλαμβάνονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στο δεσμευτικό σημείο ημερομηνίας-ώρας της διαφάνειας διάταξης και σε όλα τα θυγατρικά δεσμευτικά σημεία ημερομηνίας-ώρας. Τα θυγατρικά δεσμευτικά σημεία σημαίνουν ότι τα δεσμευτικά σημεία περιλαμβάνονται σε εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |