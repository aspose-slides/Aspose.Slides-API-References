---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των placeholder υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών placeholder.
type: docs
url: /el/com.aspose.slides/imasterslideheaderfootermanager/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Αντιπροσωπεύει το διαχειριστικό στοιχείο που διατηρεί τη συμπεριφορά των placeholder υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών placeholder. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder υποσέλιδου της κύριας διαφάνειας και όλων των παιδικών placeholder υποσέλιδων. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών placeholder αριθμών σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των παιδικών placeholder ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο placeholder υποσέλιδου της κύριας διαφάνειας και σε όλα τα παιδικά placeholder υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στο placeholder ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλα τα παιδικά placeholder ημερομηνίας-ώρας. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder υποσέλιδου της κύριας διαφάνειας και όλων των παιδικών placeholder υποσέλιδων. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα footer placeholders ορατά, διαφορετικά τα κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών placeholder αριθμών σελίδας. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα page number placeholders ορατά, διαφορετικά τα κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των παιδικών placeholder ημερομηνίας-ώρας. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα date-time placeholders ορατά, διαφορετικά τα κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στο placeholder υποσέλιδου της κύριας διαφάνειας και σε όλα τα παιδικά placeholder υποσέλιδου. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στο placeholder ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλα τα παιδικά placeholder ημερομηνίας-ώρας. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτημένες διαφάνειες διάταξης και εξαρτημένες διαφάνειες. Οι εξαρτημένες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |