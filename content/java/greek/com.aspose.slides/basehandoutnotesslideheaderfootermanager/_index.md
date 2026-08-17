---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει το διαχειριστή που διατηρεί τη συμπεριφορά των placeholders, συμπεριλαμβανομένου του placeholder κεφαλίδας για όλους τους τύπους διανομής και σημειώσεων διαφανειών.
type: docs
url: /el/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των placeholders, συμπεριλαμβανομένου του placeholder κεφαλίδας για όλες τις τύπους διανομής και σημειώσεων διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει placeholder κεφαλίδας. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder κεφαλίδας της διαφάνειας. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Ορίζει κείμενο στο placeholder κεφαλίδας της διαφάνειας. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει placeholder κεφαλίδας. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


Αλλάζει την ορατότητα του placeholder κεφαλίδας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά το placeholder κεφαλίδας ορατό, διαφορετικά - το κρύβει. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


Ορίζει κείμενο στο placeholder κεφαλίδας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |