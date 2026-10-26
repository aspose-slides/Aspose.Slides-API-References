---
title: ITheme
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα θέμα.
type: docs
url: /el/com.aspose.slides/itheme/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Αντιπροσωπεύει ένα θέμα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Επιστρέφει το χρωματικό σχήμα. |
| [getFontScheme()](#getFontScheme--) | Επιστρέφει το σχήμα γραμματοσειράς. |
| [getFormatScheme()](#getFormatScheme--) | Επιστρέφει το σχήμα μορφοποίησης σχήματος. |
| [getEffective()](#getEffective--) | Λαμβάνει τα ενεργά δεδομένα θέματος με την κληρονομιά εφαρμοσμένη. |

### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Επιστρέφει το χρωματικό σχήμα. Μόνο για ανάγνωση [IColorScheme](../../com.aspose.slides/icolorscheme).

**Επιστρέφει:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Επιστρέφει το σχήμα γραμματοσειράς. Μόνο για ανάγνωση [IFontScheme](../../com.aspose.slides/ifontscheme).

**Επιστρέφει:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Επιστρέφει το σχήμα μορφοποίησης σχήματος. Μόνο για ανάγνωση [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Επιστρέφει:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

Λαμβάνει τα ενεργά δεδομένα θέματος με την κληρονομιά εφαρμοσμένη.

**Επιστρέφει:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Ένα [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).