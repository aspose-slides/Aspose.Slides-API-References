---
title: BaseSlideHeaderFooterManager
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά το διαχειριστή που διατηρεί τη συμπεριφορά των θέσεων κράτησης υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλους τους τύπους διαφανειών.
type: docs
url: /el/com.aspose.slides/baseslideheaderfootermanager/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

Αναπαριστά το διαχειριστή που διατηρεί τη συμπεριφορά των θέσεων κράτησης υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλους τους τύπους διαφανειών.

## Μέθοδοι

| Μεθοδος | Περιγραφή |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης υποσέλιδου. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης αριθμού σελίδας. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης ημερομηνίας-ώρας. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Αλλάζει την ορατότητα της θέσης κράτησης υποσέλιδου της διαφάνειας. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Αλλάζει την ορατότητα της θέσης κράτησης αριθμού σελίδας της διαφάνειας. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Αλλάζει την ορατότητα της θέσης κράτησης ημερομηνίας-ώρας της διαφάνειας. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Ορίζει κείμενο στη θέση κράτησης υποσέλιδου της διαφάνειας. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Ορίζει κείμενο στη θέση κράτησης ημερομηνίας-ώρας της διαφάνειας. |

### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης υποσέλιδου. Διαβάζει boolean.

**Επιστρέφει:**
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης αριθμού σελίδας. Διαβάζει boolean.

**Επιστρέφει:**
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει θέση κράτησης ημερομηνίας-ώρας. Διαβάζει boolean.

**Επιστρέφει:**
boolean

### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα της θέσης κράτησης υποσέλιδου της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τη θέση κράτησης υποσέλιδου ορατή, διαφορετικά - την κρύβει. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα της θέσης κράτησης αριθμού σελίδας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τη θέση κράτησης αριθμού σελίδας ορατή, διαφορετικά - την κρύβει. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα της θέσης κράτησης ημερομηνίας-ώρας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τη θέση κράτησης ημερομηνίας-ώρας ορατή, διαφορετικά - την κρύβει. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

Ορίζει κείμενο στη θέση κράτησης υποσέλιδου της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

Ορίζει κείμενο στη θέση κράτησης ημερομηνίας-ώρας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |