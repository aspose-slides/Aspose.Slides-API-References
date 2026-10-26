---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των πλανοτήρων υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών πλανοτήρων.
type: docs
url: /el/com.aspose.slides/masterslideheaderfootermanager/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Αναπαριστά διαχειριστή που διατηρεί τη συμπεριφορά των πλανοτήρων υποσέλιδου κύριας διαφάνειας, ημερομηνίας-ώρας, αριθμού σελίδας και όλων των παιδικών πλανοτήρων. Οι παιδικοί πλανοτήρες σημαίνουν ότι οι πλανοτήρες περιλαμβάνονται σε εξαρτώμενες διαφάνειες διάταξης και σε εξαρτώμενες διαφάνειες. Οι εξαρτώμενες διαφάνειες διάταξης και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του πλανοτήρα υποσέλιδου κύριας διαφάνειας και όλων των παιδικών πλανοτήρων υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του πλανοτήρα αριθμού σελίδας κύριας διαφάνειας και όλων των παιδικών πλανοτήρων αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του πλανοτήρα ημερομηνίας-ώρας κύριας διαφάνειας και όλων των παιδικών πλανοτήρων ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο πλανοτήρα υποσέλιδου κύριας διαφάνειας και σε όλα τα παιδικά πλανοτήρια υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στο πλανοτήρα ημερομηνίας-ώρας κύριας διαφάνειας και σε όλα τα παιδικά πλανοτήρια ημερομηνίας-ώρας. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του πλανοτήρα υποσέλιδου κύριας διαφάνειας και όλων των παιδικών πλανοτήρων υποσέλιδου. Οι παιδικοί πλανοτήρες σημαίνουν ότι οι πλανοτήρες περιλαμβάνονται σε εξαρτώμενες διαφάνειες διάταξης και σε εξαρτώμενες διαφάνειες. Οι εξαρτώνται από τη κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τους πλανοτήρες υποσέλιδου ορατούς, διαφορετικά - τους κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του πλανοτήρα αριθμού σελίδας κύριας διαφάνειας και όλων των παιδικών πλανοτήρων αριθμού σελίδας. Οι παιδικοί πλανοτήρες σημαίνουν ότι οι πλανοτήρες περιλαμβάνονται σε εξαρτώμενες διαφάνειες διάταξης και σε εξαρτώμενες διαφάνειες. Οι εξαρτώνται από τη κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τους πλανοτήρες αριθμού σελίδας ορατούς, διαφορετικά - τους κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του πλανοτήρα ημερομηνίας-ώρας κύριας διαφάνειας και όλων των παιδικών πλανοτήρων ημερομηνίας-ώρας. Οι παιδικοί πλανοτήρες σημαίνουν ότι οι πλανοτήρες περιλαμβάνονται σε εξαρτώμενες διαφάνειες διάταξης και σε εξαρτώμενες διαφάνειες. Οι εξαρτώνται από τη κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τους πλανοτήρες ημερομηνίας-ώρας ορατούς, διαφορετικά - τους κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στο πλανοτήρα υποσέλιδου κύριας διαφάνειας και σε όλα τα παιδικά πλανοτήρια υποσέλιδου. Οι παιδικοί πλανοτήρες σημαίνουν ότι οι πλανοτήρες περιλαμβάνονται σε εξαρτώμενες διαφάνειες διάταξης και σε εξαρτώμενες διαφάνειες. Οι εξαρτώνται από τη κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στο πλανοτήρα ημερομηνίας-ώρας κύριας διαφάνειας και σε όλα τα παιδικά πλανοτήρια ημερομηνίας-ώρας. Οι παιδικοί πλανοτήρες σημαίνουν ότι οι πλανοτήρες περιλαμβάνονται σε εξαρτώμενες διαφάνειες διάταξης και σε εξαρτώμενες διαφάνειες. Οι εξαρτώνται από τη κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |