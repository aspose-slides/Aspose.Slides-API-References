---
title: IMasterTheme
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ένα κύριο θέμα.
type: docs
url: /el/com.aspose.slides/imastertheme/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Αντιπροσωπεύει ένα κύριο θέμα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Επιστρέφει τη συλλογή των επιπλέον σχημάτων χρωμάτων. |
| [getName()](#getName--) | Επιστρέφει το όνομα ενός θέματος. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει το όνομα ενός θέματος. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Επιστρέφει τη συλλογή των επιπλέον σχημάτων χρωμάτων. Αυτά τα σχήματα δεν επηρεάζουν την εμφάνιση της παρουσίασης, μπορούν να επιλεγούν ως κύριο σχήμα χρώματος για μια διαφάνεια. Μόνο για ανάγνωση [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Επιστρέφει:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Επιστρέφει το όνομα ενός θέματος. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Επιστρέφει το όνομα ενός θέματος. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |