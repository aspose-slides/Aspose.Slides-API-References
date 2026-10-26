---
title: IAutoShape
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει ένα AutoShape.
type: docs
url: /el/com.aspose.slides/iautoshape/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Αντιπροσωπεύει ένα AutoShape.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Επιστρέφει τα κλειδώματα του AutoShape. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει το αντικείμενο TextFrame για το AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Καθορίζει εάν αυτό το autoshape πρέπει να γεμίσει με το γέμισμα φόντου της διαφάνειας αντί για αυτό που έχει καθοριστεί από το στυλ ή τη μορφή γεμίσματος. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Καθορίζει εάν αυτό το autoshape πρέπει να γεμίσει με το γέμισμα φόντου της διαφάνειας αντί για αυτό που έχει καθοριστεί από το στυλ ή τη μορφή γεμίσματος. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Προσθέτει ένα νέο TextFrame σε ένα σχήμα. |
| [isTextBox()](#isTextBox--) | Καθορίζει εάν το σχήμα είναι πλαίσιο κειμένου. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Επιστρέφει τα κλειδώματα του AutoShape. Μόνο για ανάγνωση [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Επιστρέφει:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Επιστρέφει το αντικείμενο TextFrame για το AutoShape. Μόνο για ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Καθορίζει εάν αυτό το autoshape πρέπει να γεμίσει με το γέμισμα φόντου της διαφάνειας αντί για αυτό που έχει καθοριστεί από το στυλ ή τη μορφή γεμίσματος. Αναγνώσιμη/Εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Καθορίζει εάν αυτό το autoshape πρέπει να γεμίσει με το γέμισμα φόντου της διαφάνειας αντί για αυτό που έχει καθοριστεί από το στυλ ή τη μορφή γεμίσματος. Αναγνώσιμη/Εγγράψιμη boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Προσθέτει ένα νέο TextFrame σε ένα σχήμα. Εάν το σχήμα έχει ήδη TextFrame, τότε απλώς αλλάζει το κείμενό του.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Προεπιλεγμένο κείμενο για ένα νέο TextFrame. |

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe) - Νέο [ITextFrame](../../com.aspose.slides/itextframe) αντικείμενο.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Καθορίζει εάν το σχήμα είναι πλαίσιο κειμένου.

--------------------

Εάν το σχήμα δεν ορίζεται ως πλαίσιο κειμένου, δεν σημαίνει ότι δεν μπορεί να έχει συνδεδεμένο κείμενο. Το πλαίσιο κειμένου είναι απλώς ένα εξειδικευμένο σχήμα με συγκεκριμένες ιδιότητες.

**Επιστρέφει:**
boolean