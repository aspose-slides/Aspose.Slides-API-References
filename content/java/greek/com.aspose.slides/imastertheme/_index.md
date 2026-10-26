---
title: IMasterTheme
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά ένα κύριο θέμα.
type: docs
url: /el/com.aspose.slides/imastertheme/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Αναπαριστά ένα κύριο θέμα.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Επιστρέφει τη συλλογή των πρόσθετων σχημάτων χρωμάτων. |
| [getName()](#getName--) | Επιστρέφει το όνομα ενός θέματος. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει το όνομα ενός θέματος. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

Επιστρέφει τη συλλογή των πρόσθετων σχημάτων χρωμάτων. Αυτά τα σχήματα δεν επηρεάζουν την εμφάνιση της παρουσίασης, μπορούν να επιλεγούν ως κύριο σχήμα χρώματος για μια διαφάνεια. Μόνο προς ανάγνωση [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Επιστρέφει:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

Επιστρέφει το όνομα ενός θέματος. Αναγνώσιμη/εγγράψιμη String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Επιστρέφει το όνομα ενός θέματος. Αναγνώσιμη/εγγράψιμη String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |