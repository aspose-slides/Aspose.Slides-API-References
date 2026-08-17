---
title: IAutoShape
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά ένα AutoShape.
type: docs
url: /el/com.aspose.slides/iautoshape/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Represents an AutoShape.

## Methods

| Method | Description |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Επιστρέφει τα κλειδώματα του AutoShape. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει το αντικείμενο TextFrame για το AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Καθορίζει εάν αυτή η AutoShape πρέπει να γεμίζει με το φόντο της διαφάνειας αντί για το καθορισμένο από το στυλ ή το format γεμίσματος. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Καθορίζει εάν αυτή η AutoShape πρέπει να γεμίζει με το φόντο της διαφάνειας αντί για το καθορισμένο από το στυλ ή το format γεμίσματος. |
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

Καθορίζει εάν αυτή η AutoShape πρέπει να γεμίζει με το φόντο της διαφάνειας αντί για το καθορισμένο από το στυλ ή το format γεμίσματος. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean

### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

Καθορίζει εάν αυτή η AutoShape πρέπει να γεμίζει με το φόντο της διαφάνειας αντί για το καθορισμένο από το στυλ ή το format γεμίσματος. Αναγνώσιμη/εγγράψιμη boolean.

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

Εάν το σχήμα δεν έχει οριστεί ως πλαίσιο κειμένου, δεν σημαίνει ότι δεν μπορεί να έχει κείμενο προσαρτημένο σε αυτό. Ένα πλαίσιο κειμένου είναι απλώς ένα εξειδικευμένο σχήμα με συγκεκριμένες ιδιότητες.

**Επιστρέφει:**
boolean