---
title: ITheme
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει ένα θέμα.
type: docs
url: /el/com.aspose.slides/itheme/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Αντιπροσωπεύει ένα θέμα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Επιστρέφει το σχέδιο χρωμάτων. |
| [getFontScheme()](#getFontScheme--) | Επιστρέφει το σχέδιο γραμματοσειράς. |
| [getFormatScheme()](#getFormatScheme--) | Επιστρέφει το σχέδιο μορφοποίησης σχήματος. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα θέματος με την κληρονομικότητα που εφαρμόζεται. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Επιστρέφει το σχέδιο χρωμάτων. Μόνο για ανάγνωση [IColorScheme](../../com.aspose.slides/icolorscheme).

**Επιστρέφει:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Επιστρέφει το σχέδιο γραμματοσειράς. Μόνο για ανάγνωση [IFontScheme](../../com.aspose.slides/ifontscheme).

**Επιστρέφει:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Επιστρέφει το σχέδιο μορφοποίησης σχήματος. Μόνο για ανάγνωση [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Επιστρέφει:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Λαμβάνει τα αποτελεσματικά δεδομένα θέματος με την κληρονομικότητα που εφαρμόζεται.

**Επιστρέφει:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Ένα [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).