---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Text style formatting properties.
type: docs
url: /el/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Ιδιότητες μορφοποίησης στυλ κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Αν υπάρχει επίπεδο στυλ, το επιστρέφει, διαφορετικά επιστρέφει null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Προεπιλεγμένες ιδιότητες παραγράφου. |
| [getEffective()](#getEffective--) | Λαμβάνει τα δεδομένα μορφοποίησης του κειμένου με εφαρμοσμένη κληρονομικότητα. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Αν υπάρχει επίπεδο στυλ, το επιστρέφει, διαφορετικά επιστρέφει null.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης βάσει μηδενικής θέσης για το επίπεδο. Πρέπει να βρίσκεται στο διάστημα 0..8. |

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Μορφοποίηση του επιπέδου [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Προεπιλεγμένες ιδιότητες παραγράφου. Μόνο για ανάγνωση [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Λαμβάνει τα δεδομένα μορφοποίησης του κειμένου με εφαρμοσμένη κληρονομικότητα.

**Επιστρέφει:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Ένα [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).