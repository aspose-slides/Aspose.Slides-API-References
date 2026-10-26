---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες θέματος.
type: docs
url: /el/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες θέματος.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [ITheme](../../com.aspose.slides/itheme) για την επιστροφή αποτελεσματικών τιμών μορφοποίησης με την εφαρμογή κληρονομικότητας.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Επιστρέφει το σχήμα χρωμάτων. |
| [getFontScheme()](#getFontScheme--) | Επιστρέφει το σχήμα γραμματοσειράς. |
| [getFormatScheme()](#getFormatScheme--) | Επιστρέφει το σχήμα μορφοποίησης σχήματος. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Επιστρέφει το σχήμα χρωμάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Επιστρέφει:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - σχήμα χρωμάτων [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Επιστρέφει το σχήμα γραμματοσειράς. Μόνο για ανάγνωση [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Επιστρέφει:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Επιστρέφει το σχήμα μορφοποίησης σχήματος. Μόνο για ανάγνωση [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Επιστρέφει:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)