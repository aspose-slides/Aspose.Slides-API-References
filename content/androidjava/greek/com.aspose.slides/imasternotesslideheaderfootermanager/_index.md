---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των συμβόλων κράτησης υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης.
type: docs
url: /el/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των συμβόλων κράτησης υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας στην κύρια διαφάνεια σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης. Τα θυγατρικά σύμβολα κράτησης σημαίνουν ότι τα σύμβολα βρίσκονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Αλλάζει την ορατότητα του συμβόλου κράτησης κεφαλίδας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης κεφαλίδας. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Ορίζει κείμενο στο σύμβολο κράτησης κεφαλίδας της κύριας διαφάνειας σημειώσεων και σε όλα τα θυγατρικά σύμβολα κράτησης κεφαλίδας. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του συμβόλου κράτησης υποσέλιδου της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του συμβόλου κράτησης αριθμού σελίδας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του συμβόλου κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο σύμβολο κράτησης υποσέλιδου της κύριας διαφάνειας σημειώσεων και σε όλα τα θυγατρικά σύμβολα κράτησης υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στο σύμβολο κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και σε όλα τα θυγατρικά σύμβολα κράτησης ημερομηνίας-ώρας. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του συμβόλου κράτησης κεφαλίδας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης κεφαλίδας. Τα θυγατρικά σύμβολα κράτησης σημαίνουν ότι τα σύμβολα βρίσκονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα σύμβολα κράτησης κεφαλίδας ορατά, διαφορετικά - τα κρύβει. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Ορίζει κείμενο στο σύμβολο κράτησης κεφαλίδας της κύριας διαφάνειας σημειώσεων και σε όλα τα θυγατρικά σύμβολα κράτησης κεφαλίδας. Τα θυγατρικά σύμβολα κράτησης σημαίνουν ότι τα σύμβολα βρίσκονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του συμβόλου κράτησης υποσέλιδου της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης υποσέλιδου. Τα θυγατρικά σύμβολα κράτησης σημαίνουν ότι τα σύμβολα βρίσκονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα σύμβολα κράτησης υποσέλιδου ορατά, διαφορετικά - τα κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του συμβόλου κράτησης αριθμού σελίδας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης αριθμού σελίδας. Τα θυγατρικά σύμβολα κράτησης σημαίνουν ότι τα σύμβολα βρίσκονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα σύμβολα κράτησης αριθμού σελίδας ορατά, διαφορετικά - τα κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του συμβόλου κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και όλων των θυγατρικών συμβόλων κράτησης ημερομηνίας-ώρας. Τα θυγατρικά σύμβολα κράτησης σημαίνουν ότι τα σύμβολα βρίσκονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τα σύμβολα κράτησης ημερομηνίας-ώρας ορατά, διαφορετικά - τα κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στο σύμβολο κράτησης υποσέλιδου της κύριας διαφάνειας σημειώσεων και σε όλα τα θυγατρικά σύμβολα κράτησης υποσέλιδου. Τα θυγατρικά σύμβολα κράτησης σημαίνουν ότι τα σύμβολα βρίσκονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στο σύμβολο κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και σε όλα τα θυγατρικά σύμβολα κράτησης ημερομηνίας-ώρας. Τα θυγατρικά σύμβολα κράτησης σημαίνουν ότι τα σύμβολα βρίσκονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |