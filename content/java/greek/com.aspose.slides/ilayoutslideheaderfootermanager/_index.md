---
title: ILayoutSlideHeaderFooterManager
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει διαχειριστή που διατηρεί τη συμπεριφορά των placeholder του υποσέλιδου, της ημερομηνίας-ώρας, του αριθμού σελίδας της διαφάνειας διάταξης και όλων των παιδικών placeholder.
type: docs
url: /el/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Αντιπροσωπεύει διαχειριστή που διατηρεί τη συμπεριφορά των placeholder του υποσέλιδου, της ημερομηνίας-ώρας και του αριθμού σελίδας της διαφάνειας διάταξης καθώς και όλων των παιδικών placeholder. Οι παιδικές placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες που εξαρτώνται. Οι διαφάνειες που εξαρτώνται χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder υποσέλιδου της διαφάνειας διάταξης και όλων των παιδικών footer placeholders. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder αριθμού σελίδας της διαφάνειας διάταξης και όλων των παιδικών page number placeholders. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder ημερομηνίας-ώρας της διαφάνειας διάταξης και όλων των παιδικών date-time placeholders. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει το κείμενο στο placeholder υποσέλιδου της διαφάνειας διάταξης και όλα τα παιδικά footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει το κείμενο στο placeholder ημερομηνίας-ώρας της διαφάνειας διάταξης και όλα τα παιδικά date-time placeholders. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder υποσέλιδου της διαφάνειας διάταξης και όλων των παιδικών footer placeholders. Οι παιδικές placeholders σημαίνουν ότι τα placeholders περιλαμβάνονται σε διαφάνειες που εξαρτώνται. Οι διαφάνειες που εξαρτώνται χρησιμοποιούν και εξαρτώνται από το master slide.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα footer placeholders ορατά, διαφορετικά τα κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder αριθμού σελίδας της διαφάνειας διάταξης και όλων των παιδικών page number placeholders. Οι παιδικές placeholders σημαίνουν ότι τα placeholders περιλαμβάνονται σε διαφάνειες που εξαρτώνται. Οι διαφάνειες που εξαρτώνται χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα page number placeholders ορατά, διαφορετικά τα κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder ημερομηνίας-ώρας της διαφάνειας διάταξης και όλων των παιδικών date-time placeholders. Οι παιδικές placeholders σημαίνουν ότι τα placeholders περιλαμβάνονται σε διαφάνειες που εξαρτώνται. Οι διαφάνειες που εξαρτώνται χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα date-time placeholders ορατά, διαφορετικά τα κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ορίζει το κείμενο στο placeholder υποσέλιδου της διαφάνειας διάταξης και όλα τα παιδικά footer placeholders. Οι παιδικές placeholders σημαίνουν ότι τα placeholders περιλαμβάνονται σε διαφάνειες που εξαρτώνται. Οι διαφάνειες που εξαρτώνται χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει το κείμενο στο placeholder ημερομηνίας-ώρας της διαφάνειας διάταξης και όλα τα παιδικά date-time placeholders. Οι παιδικές placeholders σημαίνουν ότι τα placeholders περιλαμβάνονται σε διαφάνειες που εξαρτώνται. Οι διαφάνειες που εξαρτώνται χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |