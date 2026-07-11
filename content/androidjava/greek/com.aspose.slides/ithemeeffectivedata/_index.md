---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /el/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες θέματος.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [ITheme](../../com.aspose.slides/itheme) για την επιστροφή αποτελεσματικών τιμών μορφοποίησης με εφαρμοσμένη κληρονομικότητα.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |

### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```

Επιστρέφει το χρωματικό σχήμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**Επιστρέφει:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)

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