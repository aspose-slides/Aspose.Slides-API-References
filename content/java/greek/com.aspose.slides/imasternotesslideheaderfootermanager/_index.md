---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides για Java – Αναφορά API
description: Αναπαριστά διαχειριστή που διατηρεί τη συμπεριφορά των δεσμευτικών θέσης υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας της κύριας διαφάνειας σημειώσεων καθώς και όλων των παιδικών δεσμευτικών θέσης.
type: docs
url: /el/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Αντιπροσωπεύει έναν διαχειριστή που περιέχει τη συμπεριφορά του placeholder του υποσέλιδου, του placeholder της ημερομηνίας-ώρας και του placeholder του αριθμού σελίδας της κύριας διαφάνειας σημειώσεων, καθώς και όλων των παιδικών placeholder. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες σημειώσεων που εξαρτώνται. Οι διαφάνειες σημειώσεων που εξαρτώνται χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.
## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder της κεφαλίδας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών placeholder της κεφαλίδας. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Ορίζει κείμενο στο placeholder της κεφαλίδας της κύριας διαφάνειας σημειώσεων και σε όλα τα παιδικά placeholder της κεφαλίδας. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder του υποσέλιδου της κύριας διαφάνειας σημειώσεων και όλων των παιδικών placeholder του υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder του αριθμού σελίδας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών placeholder του αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder της ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών placeholder της ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο placeholder του υποσέλιδου της κύριας διαφάνειας σημειώσεων και σε όλα τα παιδικά placeholder του υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στο placeholder της ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και σε όλα τα παιδικά placeholder της ημερομηνίας-ώρας. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder της κεφαλίδας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών placeholder της κεφαλίδας. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες σημειώσεων που εξαρτώνται. Οι διαφάνειες σημειώσεων που εξαρτώνται χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholder της κεφαλίδας ορατά, διαφορετικά - τα κρύβει. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Ορίζει κείμενο στο placeholder της κεφαλίδας της κύριας διαφάνειας σημειώσεων και σε όλα τα παιδικά placeholder της κεφαλίδας. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες σημειώσεων που εξαρτώνται. Οι διαφάνειες σημειώσεων που εξαρτώνται χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Το κείμενο που θα οριστεί. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder του υποσέλιδου της κύριας διαφάνειας σημειώσεων και όλων των παιδικών placeholder του υποσέλιδου. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες σημειώσεων που εξαρτώνται. Οι διαφάνειες σημειώσεων που εξαρτώνται χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholder του υποσέλιδου ορατά, διαφορετικά - τα κρύβει. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder του αριθμού σελίδας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών placeholder του αριθμού σελίδας. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες σημειώσεων που εξαρτώνται. Οι διαφάνειες σημειώσεων που εξαρτώνται χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholder του αριθμού σελίδας ορατά, διαφορετικά - τα κρύβει. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder της ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών placeholder της ημερομηνίας-ώρας. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες σημειώσεων που εξαρτώνται. Οι διαφάνειες σημειώσεων που εξαρτώνται χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholder της ημερομηνίας-ώρας ορατά, διαφορετικά - τα κρύβει. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στο placeholder του υποσέλιδου της κύριας διαφάνειας σημειώσεων και σε όλα τα παιδικά placeholder του υποσέλιδου. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες σημειώσεων που εξαρτώνται. Οι διαφάνειες σημειώσεων που εξαρτώνται χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Το κείμενο που θα οριστεί. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στο placeholder της ημερομηνίας-ώρας της κύριας διαφάνειας σημειώσεων και σε όλα τα παιδικά placeholder της ημερομηνίας-ώρας. Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες σημειώσεων που εξαρτώνται. Οι διαφάνειες σημειώσεων που εξαρτώνται χρησιμοποιούν και εξαρτώνται από την κύρια διαφάνεια σημειώσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Το κείμενο που θα οριστεί. |