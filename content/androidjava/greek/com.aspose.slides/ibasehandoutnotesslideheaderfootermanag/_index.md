---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά έναν διαχειριστή που διατηρεί τη συμπεριφορά των placeholders, συμπεριλαμβανομένου του header placeholder για όλους τους τύπους διαφάνειας handout και notes.
type: docs
url: /el/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Αναπαριστά έναν διαχειριστή που διατηρεί τη συμπεριφορά των placeholders, συμπεριλαμβανομένου του header placeholder για όλους τους τύπους handout και notes διαφάνειες.

--------------------

Το αρχικό όνομα διεπαφής "IBaseHandoutNotesSlideHeaderFooterManager" περικόπτεται σε "IBaseHandoutNotesSlideHeaderFooterManag" για συμβατότητα COM (το μήκος του ονόματος τύπου δεν πρέπει να υπερβαίνει τους 39 χαρακτήρες).
## Methods

| Method | Description |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει ένα header placeholder. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Αλλάζει την ορατότητα του header placeholder της διαφάνειας. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Ορίζει κείμενο στο header placeholder της διαφάνειας. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει ένα header placeholder. Read boolean.

**Returns:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Αλλάζει την ορατότητα του header placeholder της διαφάνειας.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - κάνει το header placeholder ορατό, διαφορετικά - το κρύβει. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Ορίζει κείμενο στο header placeholder της διαφάνειας.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |