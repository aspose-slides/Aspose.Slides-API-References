---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει ιδιότητες αποτελεσματικού στυλ κειμένου.
type: docs
url: /el/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει ιδιότητες αποτελεσματικού στυλ κειμένου.

--------------------

This interface is used together with the [ITextStyle](../../com.aspose.slides/itextstyle) interface to return effective formatting values with inheritance applied.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Επιστρέφει το επίπεδο του αποτελεσματικού στυλ. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Επιστρέφει τις αποτελεσματικές προεπιλεγμένες ιδιότητες παραγράφου. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


Επιστρέφει το επίπεδο του αποτελεσματικού στυλ.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης αρχής μηδέν του επιπέδου. Πρέπει να βρίσκεται στο διάστημα 0..8. |

**Επιστρέφει:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Αποτελεσματική μορφοποίηση του επιπέδου [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


Επιστρέφει τις αποτελεσματικές προεπιλεγμένες ιδιότητες παραγράφου. Μόνο ανάγνωση [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Επιστρέφει:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)