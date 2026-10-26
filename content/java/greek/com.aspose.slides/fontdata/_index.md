---
title: FontData
second_title: Aspose.Slides για το API της Java
description: Αναπαριστά έναν ορισμό γραμματοσειράς.
type: docs
url: /el/com.aspose.slides/fontdata/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Αναπαριστά έναν ορισμό γραμματοσειράς. Αμετάβλητο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Creates a new FontData object with the specified font name. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontName()](#getFontName--) | Επιστρέφει το όνομα της γραμματοσειράς. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Επιστρέφει το όνομα της γραμματοσειράς, αντικαθιστώντας την αναφορά θέματος με την πραγματική χρησιμοποιούμενη γραμματοσειρά. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν δύο στιγμιότυπα FontData είναι ισοδύναμα. |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως ο πίνακας κατακερματισμού. |
| [toString()](#toString--) | Επιστρέφει την αναπαράσταση ως συμβολοσειρά. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Creates a new FontData object with the specified font name.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Όνομα γραμματοσειράς. |
### getFontName() {#getFontName--}
```
public final String getFontName()
```

Επιστρέφει το όνομα της γραμματοσειράς. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Επιστρέφει το όνομα της γραμματοσειράς, αντικαθιστώντας την αναφορά θέματος με την πραγματική χρησιμοποιούμενη γραμματοσειρά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Το θέμα από το οποίο πρέπει να ληφθεί το ονομαστικό όνομα της γραμματοσειράς. Εξαρτάται από τον καλούντα να παρέχει τη σωστή τιμή. Δείτε [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Επιστρέφει:**
java.lang.String - Όνομα γραμματοσειράς.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν δύο στιγμιότυπα FontData είναι ισοδύναμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το FontData προς σύγκριση με το τρέχον FontData. |

**Επιστρέφει:**
boolean - **true** εάν το καθορισμένο FontData είναι ίσο με το τρέχον FontData· διαφορετικά, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως ο πίνακας κατακερματισμού.

**Επιστρέφει:**
int - Κώδικας κατακερματισμού του FontData.
### toString() {#toString--}
```
public String toString()
```

Επιστρέφει την αναπαράσταση ως συμβολοσειρά.

**Επιστρέφει:**
java.lang.String - Συμβολοσειρά αναπαράστασης.