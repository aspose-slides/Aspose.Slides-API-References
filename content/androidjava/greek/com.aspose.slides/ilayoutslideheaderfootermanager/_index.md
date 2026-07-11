---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει το διαχειριστή που διαχειρίζεται τη συμπεριφορά των εικονιδίων υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της διαφάνειας διάταξης και όλων των θυγατρικών εικονιδίων.
type: docs
url: /el/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Αντιπροσωπεύει διαχειριστή που διαχειρίζεται τη συμπεριφορά των εικονιδίων υποσέλιδου διαφάνειας διάταξης, ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών εικονιδίων. Τα θυγατρικά εικονίδια σημαίνουν ότι τα εικονίδια περιλαμβάνονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

## Μέθοδοι

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του εικονιδίου υποσέλιδου διαφάνειας διάταξης και όλων των θυγατρικών εικονιδίων υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του εικονιδίου αριθμού σελίδας διαφάνειας διάταξης και όλων των θυγατρικών εικονιδίων αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του εικονιδίου ημερομηνίας-ώρας διαφάνειας διάταξης και όλων των θυγατρικών εικονιδίων ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο εικονίδιο υποσέλιδου διαφάνειας διάταξης και σε όλα τα θυγατρικά εικονίδια υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στο εικονίδιο ημερομηνίας-ώρας διαφάνειας διάταξης και σε όλα τα θυγατρικά εικονίδια ημερομηνίας-ώρας. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του εικονιδίου υποσέλιδου διαφάνειας διάταξης και όλων των θυγατρικών εικονιδίων υποσέλιδου. Τα θυγατρικά εικονίδια σημαίνουν ότι τα εικονίδια περιλαμβάνονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια master.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα εικονίδια υποσέλιδου ορατά, διαφορετικά τα κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του εικονιδίου αριθμού σελίδας διαφάνειας διάταξης και όλων των θυγατρικών εικονιδίων αριθμού σελίδας. Τα θυγατρικά εικονίδια σημαίνουν ότι τα εικονίδια περιλαμβάνονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα εικονίδια αριθμού σελίδας ορατά, διαφορετικά τα κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του εικονιδίου ημερομηνίας-ώρας διαφάνειας διάταξης και όλων των θυγατρικών εικονιδίων ημερομηνίας-ώρας. Τα θυγατρικά εικονίδια σημαίνουν ότι τα εικονίδια περιλαμβάνονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα εικονίδια ημερομηνίας-ώρας ορατά, διαφορετικά τα κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στο εικονίδιο υποσέλιδου διαφάνειας διάταξης και σε όλα τα θυγατρικά εικονίδια υποσέλιδου. Τα θυγατρικά εικονίδια σημαίνουν ότι τα εικονίδια περιλαμβάνονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στο εικονίδιο ημερομηνίας-ώρας διαφάνειας διάταξης και σε όλα τα θυγατρικά εικονίδια ημερομηνίας-ώρας. Τα θυγατρικά εικονίδια σημαίνουν ότι τα εικονίδια περιλαμβάνονται σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |