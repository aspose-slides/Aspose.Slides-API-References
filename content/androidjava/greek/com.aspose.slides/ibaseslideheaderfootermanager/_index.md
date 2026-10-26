---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει διαχειριστή που διατηρεί τη συμπεριφορά των σύμβολων υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλους τους τύπους διαφανειών.
type: docs
url: /el/com.aspose.slides/ibaseslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Represents manager which holds behavior of the footer, date-time, page number placeholders for all slide types.

## Methods

| Method | Description |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο υποσέλιδου. Ανάγνωση boolean. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο αριθμού σελίδας. Ανάγνωση boolean. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο ημερομηνίας-ώρας. Ανάγνωση boolean. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Αλλάζει την ορατότητα του συμβόλου υποσέλιδου της διαφάνειας. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Αλλάζει την ορατότητα του συμβόλου αριθμού σελίδας της διαφάνειας. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Αλλάζει την ορατότητα του συμβόλου ημερομηνίας-ώρας της διαφάνειας. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Ορίζει κείμενο στο σύμβολο υποσέλιδου της διαφάνειας. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Ορίζει κείμενο στο σύμβολο ημερομηνίας-ώρας της διαφάνειας. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο υποσέλιδου. Read boolean.

**Returns:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο αριθμού σελίδας. Read boolean.

**Returns:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει σύμβολο ημερομηνίας-ώρας. Read boolean.

**Returns:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του συμβόλου υποσέλιδου της διαφάνειας.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά το σύμβολο υποσέλιδου ορατό, διαφορετικά - το κρύβει. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του συμβόλου αριθμού σελίδας της διαφάνειας.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά το σύμβολο αριθμού σελίδας ορατό, διαφορετικά - το κρύβει. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του συμβόλου ημερομηνίας-ώρας της διαφάνειας.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά το σύμβολο ημερομηνίας-ώρας ορατό, διαφορετικά - το κρύβει. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Ορίζει κείμενο στο σύμβολο υποσέλιδου της διαφάνειας.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Ορίζει κείμενο στο σύμβολο ημερομηνίας-ώρας της διαφάνειας.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |