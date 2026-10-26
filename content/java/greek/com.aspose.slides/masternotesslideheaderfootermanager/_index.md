---
title: MasterNotesSlideHeaderFooterManager
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των υποδοχέων υποσέλιδου, ημερομηνίας-ώρας, αριθμού σελίδας της κύριας διαφάνειας σημειώσεων και όλων των παιδικών υποδοχέων.
type: docs
url: /el/com.aspose.slides/masternotesslideheaderfootermanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

Αντιπροσωπεύει τον διαχειριστή που κρατά τη συμπεριφορά του υποσέλιδου διαφάνειας κύριων σημειώσεων, της ημερομηνίας-ώρας, των υποδοχέων αριθμού σελίδας και όλων των παιδικών υποδοχέων. Τα παιδικά υποδοχείς σημαίνουν ότι οι υποδοχείς περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη διαφάνεια κύριων σημειώσεων.
## Methods

| Method | Description |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Αλλάζει την ορατότητα του υποδοχέα κεφαλίδας της διαφάνειας κύριων σημειώσεων και όλων των παιδικών υποδοχέων κεφαλίδας. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Ορίζει κείμενο στο υποδοχέα κεφαλίδας της διαφάνειας κύριων σημειώσεων και σε όλους τους παιδικούς υποδοχείς κεφαλίδας. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Αλλάζει την ορατότητα του υποδοχέα υποσέλιδου της κύριας διαφάνειας και όλων των παιδικών υποδοχέων υποσέλιδου. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα του υποδοχέα αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών υποδοχέων αριθμού σελίδας. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα του υποδοχέα ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των παιδικών υποδοχέων ημερομηνίας-ώρας. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ορίζει κείμενο στο υποδοχέα υποσέλιδου της κύριας διαφάνειας και σε όλους τους παιδικούς υποδοχείς υποσέλιδου. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ορίζει κείμενο στο υποδοχέα ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλους τους παιδικούς υποδοχείς ημερομηνίας-ώρας. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποδοχέα κεφαλίδας της διαφάνειας κύριων σημειώσεων και όλων των παιδικών υποδοχών κεφαλίδας. Τα παιδικά υποδοχείς σημαίνουν ότι οι υποδοχείς περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη διαφάνεια κύριων σημειώσεων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τους υποδοχείς κεφαλίδας ορατούς, διαφορετικά - τους κρύβει. |
### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

Ορίζει κείμενο στο υποδοχέα κεφαλίδας της διαφάνειας κύριων σημειώσεων και σε όλους τους παιδικούς υποδοχείς κεφαλίδας. Τα παιδικά υποδοχείς σημαίνουν ότι οι υποδοχείς περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη διαφάνεια κύριων σημειώσεων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποδοχέα υποσέλιδου της κύριας διαφάνειας και όλων των παιδικών υποδοχέων υποσέλιδου. Τα παιδικά υποδοχείς σημαίνουν ότι οι υποδοχείς περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη διαφάνεια κύριων σημειώσεων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τους υποδοχείς υποσέλιδου ορατούς, διαφορετικά - τους κρύβει. |
### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποδοχέα αριθμού σελίδας της κύριας διαφάνειας και όλων των παιδικών υποδοχέων αριθμού σελίδας. Τα παιδικά υποδοχείς σημαίνουν ότι οι υποδοχείς περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη διαφάνεια κύριων σημειώσεων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τους υποδοχείς αριθμού σελίδας ορατούς, διαφορετικά - τους κρύβει. |
### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποδοχέα ημερομηνίας-ώρας της κύριας διαφάνειας και όλων των παιδικών υποδοχέων ημερομηνίας-ώρας. Τα παιδικά υποδοχείς σημαίνουν ότι οι υποδοχείς περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη διαφάνεια κύριων σημειώσεων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τους υποδοχείς ημερομηνίας-ώρας ορατούς, διαφορετικά - τους κρύβει. |
### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Ορίζει κείμενο στο υποδοχέα υποσέλιδου της κύριας διαφάνειας και σε όλους τους παιδικούς υποδοχείς υποσέλιδου. Τα παιδικά υποδοχείς σημαίνουν ότι οι υποδοχείς περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη διαφάνεια κύριων σημειώσεων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |
### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Ορίζει κείμενο στο υποδοχέα ημερομηνίας-ώρας της κύριας διαφάνειας και σε όλους τους παιδικούς υποδοχείς ημερομηνίας-ώρας. Τα παιδικά υποδοχείς σημαίνουν ότι οι υποδοχείς περιέχονται σε εξαρτώμενες διαφάνειες σημειώσεων. Οι εξαρτώμενες διαφάνειες σημειώσεων χρησιμοποιούν και εξαρτώνται από τη διαφάνεια κύριων σημειώσεων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |