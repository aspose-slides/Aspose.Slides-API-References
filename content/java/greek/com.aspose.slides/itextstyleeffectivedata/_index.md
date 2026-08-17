---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες στυλ κειμένου.
type: docs
url: /el/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες στυλ κειμένου.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [ITextStyle](../../com.aspose.slides/itextstyle) για την επιστροφή των αποτελεσματικών τιμών μορφοποίησης με την κληρονομικότητα εφαρμοσμένη.
## Methods

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Returns level of effective style. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Returns effective default paragraph properties. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Επιστρέφει το επίπεδο του αποτελεσματικού στυλ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης μηδενικής βάσης του επιπέδου. Πρέπει να βρίσκεται στο διάστημα 0..8. |

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Αποτελεσματική μορφοποίηση του επιπέδου [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Επιστρέφει τις αποτελεσματικές προεπιλεγμένες ιδιότητες παραγράφου. Μόνο για ανάγνωση [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)