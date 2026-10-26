---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά διαχειριστή που διατηρεί τη συμπεριφορά των ετικετών υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας και όλων των θυγατρικών ετικετών.
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

Αναπαριστά διαχειριστή που διατηρεί τη συμπεριφορά του υποσέλιδου της κύριας διαφάνειας, των ετικετών ημερομηνίας-ώρας, αριθμού σελίδας και όλων των θυγατρικών ετικετών. Οι θυγατρικές ετικέτες σημαίνουν ότι οι ετικέτες περιλαμβάνονται σε διαφάνειες εξαρτημένων διατάξεων και σε εξαρτώμενες διαφάνειες. Οι διαφάνειες εξαρτημένων διατάξεων και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του υποσέλιδου της κύριας διαφάνειας και όλων των θυγατρικών υποσέλιδων. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του αριθμού σελίδας της κύριας διαφάνειας και όλων των θυγατρικών αριθμών σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα της ετικέτας ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των θυγατρικών ετικετών ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο υποσέλιδο της κύριας διαφάνειας και σε όλα τα θυγατρικά υποσέλιδα. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στην ετικέτα ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλα τα θυγατρικά στοιχεία ημερομηνίας-ώρας. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


Αλλάζει την ορατότητα του υποσέλιδου της κύριας διαφάνειας και όλων των θυγατρικών υποσέλιδων. Οι θυγατρικές ετικέτες σημαίνουν ότι οι ετικέτες περιλαμβάνονται σε διαφάνειες εξαρτημένων διατάξεων και σε εξαρτώμενες διαφάνειες. Οι διαφάνειες εξαρτημένων διατάξεων και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - εμφανίζει τις ετικέτες υποσέλιδου, διαφορετικά - τις κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Αλλάζει την ορατότητα του αριθμού σελίδας της κύριας διαφάνειας και όλων των θυγατρικών αριθμών σελίδας. Οι θυγατρικές ετικέτες σημαίνουν ότι οι ετικέτες περιλαμβάνονται σε διαφάνειες εξαρτημένων διατάξεων και σε εξαρτώμενες διαφάνειες. Οι διαφάνειες εξαρτημένων διατάξεων και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - εμφανίζει τις ετικέτες αριθμού σελίδας, διαφορετικά - τις κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Αλλάζει την ορατότητα της ετικέτας ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των θυγατρικών ετικετών ημερομηνίας-ώρας. Οι θυγατρικές ετικέτες σημαίνουν ότι οι ετικέτες περιλαμβάνονται σε διαφάνειες εξαρτημένων διατάξεων και σε εξαρτώμενες διαφάνειες. Οι διαφάνειες εξαρτημένων διατάξεων και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - εμφανίζει τις ετικέτες ημερομηνίας-ώρας, διαφορετικά - τις κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


Ορίζει κείμενο στο υποσέλιδο της κύριας διαφάνειας και σε όλα τα θυγατρικά υποσέλιδα. Οι θυγατρικές ετικέτες σημαίνουν ότι οι ετικέτες περιλαμβάνονται σε διαφάνειες εξαρτημένων διατάξεων και σε εξαρτώμενες διαφάνειες. Οι διαφάνειες εξαρτημένων διατάξεων και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


Ορίζει κείμενο στην ετικέτα ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλα τα θυγατρικά στοιχεία ημερομηνίας-ώρας. Οι θυγατρικές ετικέτες σημαίνουν ότι οι ετικέτες περιλαμβάνονται σε διαφάνειες εξαρτημένων διατάξεων και σε εξαρτώμενες διαφάνειες. Οι διαφάνειες εξαρτημένων διατάξεων και οι διαφάνειες χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |