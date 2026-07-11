---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των υποσημειωμάτων υποσέλιδου διάταξης, ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών υποσημειωμάτων.
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

Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά του υποσημειώματος υποσέλιδου διάταξης, του υποσημειώματος ημερομηνίας-ώρας, του υποσημειώματος αριθμού σελίδας και όλων των θυγατρικών υποσημειωμάτων. Τα θυγατρικά υποσημειώματα σημαίνουν ότι τα υποσημειώματα περιλαμβάνονται στις εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του υποσημειώματος υποσέλιδου διάταξης και όλων των θυγατρικών υποσημειωμάτων υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του υποσημειώματος αριθμού σελίδας διάταξης και όλων των θυγατρικών υποσημειωμάτων αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του υποσημειώματος ημερομηνίας-ώρας διάταξης και όλων των θυγατρικών υποσημειωμάτων ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο υποσημείο υποσέλιδου διάταξης και σε όλα τα θυγατρικά υποσημειώματα υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στο υποσημείο ημερομηνίας-ώρας διάταξης και σε όλα τα θυγατρικά υποσημειώματα ημερομηνίας-ώρας. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποσημειώματος υποσέλιδου διάταξης και όλων των θυγατρικών υποσημειωμάτων υποσέλιδου. Τα θυγατρικά υποσημειώματα σημαίνουν ότι τα υποσημειώματα περιλαμβάνονται στις εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια master.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα υποσημειώματα υποσέλιδου ορατά, διαφορετικά - τα κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποσημειώματος αριθμού σελίδας διάταξης και όλων των θυγατρικών υποσημειωμάτων αριθμού σελίδας. Τα θυγατρικά υποσημειώματα σημαίνουν ότι τα υποσημειώματα περιλαμβάνονται στις εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα υποσημειώματα αριθμού σελίδας ορατά, διαφορετικά - τα κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποσημειώματος ημερομηνίας-ώρας διάταξης και όλων των θυγατρικών υποσημειωμάτων ημερομηνίας-ώρας. Τα θυγατρικά υποσημειώματα σημαίνουν ότι τα υποσημειώματα περιλαμβάνονται στις εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα υποσημειώματα ημερομηνίας-ώρας ορατά, διαφορετικά - τα κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στο υποσημείο υποσέλιδου διάταξης και σε όλα τα θυγατρικά υποσημειώματα υποσέλιδου. Τα θυγατρικά υποσημειώματα σημαίνουν ότι τα υποσημειώματα περιλαμβάνονται στις εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στο υποσημείο ημερομηνίας-ώρας διάταξης και σε όλα τα θυγατρικά υποσημειώματα ημερομηνίας-ώρας. Τα θυγατρικά υποσημειώματα σημαίνουν ότι τα υποσημειώματα περιλαμβάνονται στις εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |