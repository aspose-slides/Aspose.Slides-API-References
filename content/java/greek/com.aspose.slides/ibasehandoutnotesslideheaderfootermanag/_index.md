---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides για την Java API Αναφορά
description: Αντιπροσωπεύει έναν διαχειριστή που διατηρεί τη συμπεριφορά των placeholders, συμπεριλαμβανομένου του placeholder κεφαλίδας για όλα τα είδη διαφανειών διανομής και σημειώσεων.
type: docs
url: /el/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Αντιπροσωπεύει έναν διαχειριστή που διατηρεί τη συμπεριφορά των placeholders, συμπεριλαμβανομένου του placeholder κεφαλίδας για όλα τα είδη διαφανειών διανομής και σημειώσεων.

--------------------

Το αρχικό όνομα διεπαφής "IBaseHandoutNotesSlideHeaderFooterManager" είναι συντομευμένο σε "IBaseHandoutNotesSlideHeaderFooterManag" για συμβατότητα με COM (το μήκος του ονόματος τύπου δεν πρέπει να υπερβαίνει τα 39).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει placeholder κεφαλίδας. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Αλλάζει την ορατότητα του placeholder κεφαλίδας της διαφάνειας. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Ορίζει κείμενο στο placeholder κεφαλίδας της διαφάνειας. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει placeholder κεφαλίδας. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα του placeholder κεφαλίδας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά το placeholder κεφαλίδας ορατό, διαφορετικά - το κρύβει. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Ορίζει κείμενο στο placeholder κεφαλίδας της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Το κείμενο προς ορισμό. |