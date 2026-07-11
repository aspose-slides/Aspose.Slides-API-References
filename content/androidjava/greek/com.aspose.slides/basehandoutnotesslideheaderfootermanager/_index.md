---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά των placeholders, συμπεριλαμβανομένου του header placeholder για όλους τους τύπους handout και notes διαφανειών.
type: docs
url: /el/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

Αντιπροσωπεύει το διαχειριστή που διατηρεί τη συμπεριφορά των placeholders, συμπεριλαμβανομένου του header placeholder για όλους τους τύπους διαφάνειας handout και notes.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει ένα header placeholder. Διαβάζει boolean. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Αλλάζει τη ορατότητα του header placeholder της διαφάνειας. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Ορίζει κείμενο στο header placeholder της διαφάνειας. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


Λαμβάνει την τιμή που υποδεικνύει ότι υπάρχει ένα header placeholder. Διαβάζει boolean.

**Επιστρέφει:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


Αλλάζει τη ορατότητα του header placeholder της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά ορατό το header placeholder, διαφορετικά - το κρύβει. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


Ορίζει κείμενο στο header placeholder της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |