---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides για την Αναφορά API Java
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των αντικειμένων κράτησης θέσης υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλους τους τύπους διαφάνειας.
type: docs
url: /el/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Αντιπροσωπεύει διαχειριστή που διατηρεί τη συμπεριφορά των αντικειμένων κράτησης θέσης υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλους τους τύπους διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Λαμβάνει τιμή που υποδεικνύει την παρουσία αντικειμένου κράτησης θέσης υποσέλιδου. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Λαμβάνει τιμή που υποδεικνύει την παρουσία αντικειμένου κράτησης θέσης αριθμού σελίδας. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Λαμβάνει τιμή που υποδεικνύει την παρουσία αντικειμένου κράτησης θέσης ημερομηνίας-ώρας. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης υποσέλιδου της διαφάνειας. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης αριθμού σελίδας της διαφάνειας. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Ορίζει κείμενο στο αντικείμενο κράτησης θέσης υποσέλιδου της διαφάνειας. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Ορίζει κείμενο στο αντικείμενο κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Λαμβάνει τιμή που υποδεικνύει την παρουσία αντικειμένου κράτησης θέσης υποσέλιδου. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Λαμβάνει τιμή που υποδεικνύει την παρουσία αντικειμένου κράτησης θέσης αριθμού σελίδας. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Λαμβάνει τιμή που υποδεικνύει την παρουσία αντικειμένου κράτησης θέσης ημερομηνίας-ώρας. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης υποσέλιδου της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει το αντικείμενο κράτησης θέσης υποσέλιδου ορατό, διαφορετικά το κρύβει. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης αριθμού σελίδας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει το αντικείμενο κράτησης θέσης αριθμού σελίδας ορατό, διαφορετικά το κρύβει. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του αντικειμένου κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - κάνει το αντικείμενο κράτησης θέσης ημερομηνίας-ώρας ορατό, διαφορετικά το κρύβει. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Ορίζει κείμενο στο αντικείμενο κράτησης θέσης υποσέλιδου της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Ορίζει κείμενο στο αντικείμενο κράτησης θέσης ημερομηνίας-ώρας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |