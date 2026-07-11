---
title: MasterTheme
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει ένα κύριο θέμα.
type: docs
url: /el/com.aspose.slides/mastertheme/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Αντιπροσωπεύει ένα κύριο θέμα.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Επιστρέφει το χρωματικό σχήμα. |
| [getFontScheme()](#getFontScheme--) | Επιστρέφει το σχήμα γραμματοσειράς. |
| [getFormatScheme()](#getFormatScheme--) | Επιστρέφει το σχήμα μορφοποίησης σχήματος. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Επιστρέφει τη συλλογή των πρόσθετων χρωματικών σχημάτων. |
| [getName()](#getName--) | Επιστρέφει το όνομα ενός θέματος. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει το όνομα ενός θέματος. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


Επιστρέφει το χρωματικό σχήμα. Μόνο για ανάγνωση [IColorScheme](../../com.aspose.slides/icolorscheme).

**Επιστρέφει:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


Επιστρέφει το σχήμα γραμματοσειράς. Μόνο για ανάγνωση [IFontScheme](../../com.aspose.slides/ifontscheme).

**Επιστρέφει:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


Επιστρέφει το σχήμα μορφοποίησης σχήματος. Μόνο για ανάγνωση [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Επιστρέφει:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


Επιστρέφει τη συλλογή των πρόσθετων χρωματικών σχημάτων. Αυτά τα σχήματα δεν επηρεάζουν την εμφάνιση της παρουσίασης, μπορούν να επιλεγούν ως κύριο χρωματικό σχήμα για μια διαφάνεια. Μόνο για ανάγνωση [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Επιστρέφει:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


Επιστρέφει το όνομα ενός θέματος. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Επιστρέφει το όνομα ενός θέματος. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long