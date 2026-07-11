---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει τη διαχειριστική μονάδα που διατηρεί τη συμπεριφορά των θέσεων κράτησης υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας της κύριας διαφάνειας σημειώσεων, καθώς και όλων των παιδικών θέσεων κράτησης.
type: docs
url: /el/com.aspose.slides/masternotesslideheaderfootermanager/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

Αντιπροσωπεύει τη διαχειριστική μονάδα που διατηρεί τη συμπεριφορά του υποσέλιδου, της ημερομηνίας-ώρας και των θέσεων αριθμού σελίδας της κύριας διαφάνειας σημειώσεων, καθώς και όλων των παιδικών θέσεων κράτησης. Οι παιδικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτημένες διαφάνειες σημειώσεων. Οι εξαρτημένες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Αλλάζει την ορατότητα της θέσης κράτησης κεφαλίδας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών θέσεων κράτησης κεφαλίδας. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Ορίζει κείμενο στη θέση κράτησης κεφαλίδας της κύριας διαφάνειας σημειώσεων και σε όλες τις παιδικές θέσεις κράτησης κεφαλίδας. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα της θέσης κράτησης υποσέλιδου της κύριας διαφάνειας και όλων των παιδικών θέσεων κράτησης υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα της θέσης κράτησης αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών θέσεων κράτησης αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα της θέσης κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των παιδικών θέσεων κράτησης ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στη θέση κράτησης υποσέλιδου της κύριας διαφάνειας και σε όλες τις παιδικές θέσεις κράτησης υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στη θέση κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλες τις παιδικές θέσεις κράτησης ημερομηνίας-ώρας. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα της θέσης κράτησης κεφαλίδας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών θέσεων κράτησης κεφαλίδας. Οι παιδικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτημένες διαφάνειες σημειώσεων. Οι εξαρτημένες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τις θέσεις κράτησης κεφαλίδας ορατές, αλλιώς - τις κρύβει. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

Ορίζει κείμενο στη θέση κράτησης κεφαλίδας της κύριας διαφάνειας σημειώσεων και σε όλες τις παιδικές θέσεις κράτησης κεφαλίδας. Οι παιδικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτημένες διαφάνειες σημειώσεων. Οι εξαρτημένες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα της θέσης κράτησης υποσέλιδου της κύριας διαφάνειας και όλων των παιδικών θέσεων κράτησης υποσέλιδου. Οι παιδικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτημένες διαφάνειες σημειώσεων. Οι εξαρτημένες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τις θέσεις κράτησης υποσέλιδου ορατές, αλλιώς - τις κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα της θέσης κράτησης αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών θέσεων κράτησης αριθμού σελίδας. Οι παιδικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτημένες διαφάνειες σημειώσεων. Οι εξαρτημένες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τις θέσεις κράτησης αριθμού σελίδας ορατές, αλλιώς - τις κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα της θέσης κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των παιδικών θέσεων κράτησης ημερομηνίας-ώρας. Οι παιδικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτημένες διαφάνειες σημειώσεων. Οι εξαρτημένες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τις θέσεις κράτησης ημερομηνίας-ώρας ορατές, αλλιώς - τις κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στη θέση κράτησης υποσέλιδου της κύριας διαφάνειας και σε όλες τις παιδικές θέσεις κράτησης υποσέλιδου. Οι παιδικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτημένες διαφάνειες σημειώσεων. Οι εξαρτημένες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στη θέση κράτησης ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλες τις παιδικές θέσεις κράτησης ημερομηνίας-ώρας. Οι παιδικές θέσεις κράτησης σημαίνουν ότι οι θέσεις είναι περιεχόμενες σε εξαρτημένες διαφάνειες σημειώσεων. Οι εξαρτημένες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |