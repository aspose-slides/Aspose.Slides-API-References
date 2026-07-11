---
title: FontData
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
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
| [FontData(String fontName)](#FontData-java.lang.String-) | Δημιουργεί ένα νέο αντικείμενο FontData με το καθορισμένο όνομα γραμματοσειράς. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontName()](#getFontName--) | Επιστρέφει το όνομα της γραμματοσειράς. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Επιστρέφει το όνομα της γραμματοσειράς, αντικαθιστώντας την αναφορά θέματος με μια πραγματική γραμματοσειρά που χρησιμοποιείται. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν δύο αντικείμενα FontData είναι ίσα. |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού. |
| [toString()](#toString--) | Επιστρέφει την αναπαράσταση κειμένου. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```


Δημιουργεί ένα νέο αντικείμενο FontData με το καθορισμένο όνομα γραμματοσειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Όνομα γραμματοσειράς. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Επιστρέφει το όνομα της γραμματοσειράς. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```


Επιστρέφει το όνομα της γραμματοσειράς, αντικαθιστώντας την αναφορά θέματος με μια πραγματική γραμματοσειρά που χρησιμοποιείται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Θέμα από το οποίο πρέπει να ληφθεί το όνομα γραμματοσειράς του θέματος. Εξαρτάται από τον καλούντα να παρέχει μια σωστή τιμή. Δείτε [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Επιστρέφει:**
java.lang.String - Όνομα γραμματοσειράς.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει αν δύο αντικείμενα FontData είναι ίσα.

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


Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.

**Επιστρέφει:**
int - Κώδικας κατακερματισμού του FontData.
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει την αναπαράσταση κειμένου.

**Επιστρέφει:**
java.lang.String - Αναπαράσταση κειμένου.