---
title: BaseSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των υποδοχέων υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλους τους τύπους διαφάνειας.
type: docs
url: /el/com.aspose.slides/baseslideheaderfootermanager/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των υποδοχέων υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλους τους τύπους διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει υποδοχέας υποσέλιδου. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει υποδοχέας αριθμού σελίδας. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει υποδοχέας ημερομηνίας-ώρας. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Αλλάζει την ορατότητα του υποδοχέα υποσέλιδου στη διαφάνεια. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Αλλάζει την ορατότητα του υποδοχέα αριθμού σελίδας στη διαφάνεια. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Αλλάζει την ορατότητα του υποδοχέα ημερομηνίας-ώρας στη διαφάνεια. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Ορίζει κείμενο για τον υποδοχέα υποσέλιδου της διαφάνειας. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Ορίζει κείμενο για τον υποδοχέα ημερομηνίας-ώρας της διαφάνειας. |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει υποδοχέας υποσέλιδου. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει υποδοχέας αριθμού σελίδας. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει υποδοχέας ημερομηνίας-ώρας. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποδοχέα υποσέλιδου στη διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τον υποδοχέα υποσέλιδου ορατό, διαφορετικά - τον κρύβει. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποδοχέα αριθμού σελίδας στη διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τον υποδοχέα αριθμού σελίδας ορατό, διαφορετικά - τον κρύβει. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του υποδοχέα ημερομηνίας-ώρας στη διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει τον υποδοχέα ημερομηνίας-ώρας ορατό, διαφορετικά - τον κρύβει. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

Ορίζει κείμενο για τον υποδοχέα υποσέλιδου της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

Ορίζει κείμενο για τον υποδοχέα ημερομηνίας-ώρας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |