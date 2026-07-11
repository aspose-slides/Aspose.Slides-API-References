---
title: IOverrideTheme
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά ένα αντικαταστατικό θέμα.
type: docs
url: /el/com.aspose.slides/ioverridetheme/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Αναπαριστά ένα αντικαταστατικό θέμα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isEmpty()](#isEmpty--) | Η τιμή true σημαίνει ότι το ColorScheme, FontScheme, FormatScheme είναι null και οποιαδήποτε αντικατάσταση με αυτό το αντικείμενο θέματος είναι απενεργοποιημένη. |
| [initColorScheme()](#initColorScheme--) | Αρχικοποιεί το ColorScheme με νέο αντικείμενο για αντικατάσταση του ColorScheme του InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Αρχικοποιεί το ColorScheme με νέο αντικείμενο για αντικατάσταση του ColorScheme του InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Αρχικοποιεί το ColorScheme με νέο αντικείμενο για αντικατάσταση του ColorScheme του InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Αρχικοποιεί το FontScheme με νέο αντικείμενο για αντικατάσταση του FontScheme του InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Αρχικοποιεί το FontScheme με νέο αντικείμενο για αντικατάσταση του FontScheme του InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Αρχικοποιεί το FontScheme με νέο αντικείμενο για αντικατάσταση του FontScheme του InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Αρχικοποιεί το FormatScheme με νέο αντικείμενο για αντικατάσταση του FormatScheme του InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Αρχικοποιεί το FormatScheme με νέο αντικείμενο για αντικατάσταση του FormatScheme του InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Αρχικοποιεί το FormatScheme με νέο αντικείμενο για αντικατάσταση του FormatScheme του InheritedTheme. |
| [clear()](#clear--) | Ορίζει το ColorScheme, FontScheme, FormatScheme σε null για να απενεργοποιήσει οποιαδήποτε αντικατάσταση με αυτό το αντικείμενο θέματος. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Η τιμή true σημαίνει ότι το ColorScheme, FontScheme, FormatScheme είναι null και οποιαδήποτε αντικατάσταση με αυτό το αντικείμενο θέματος είναι απενεργοποιημένη. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Αρχικοποιεί το ColorScheme με νέο αντικείμενο για αντικατάσταση του ColorScheme του InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Αρχικοποιεί το ColorScheme με νέο αντικείμενο για αντικατάσταση του ColorScheme του InheritedTheme.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Δεδομένα για αρχικοποίηση. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Αρχικοποιεί το ColorScheme με νέο αντικείμενο για αντικατάσταση του ColorScheme του InheritedTheme. Και αρχικοποιεί τα δεδομένα του νέου αντικειμένου με τα δεδομένα του ColorScheme του InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Αρχικοποιεί το FontScheme με νέο αντικείμενο για αντικατάσταση του FontScheme του InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Αρχικοποιεί το FontScheme με νέο αντικείμενο για αντικατάσταση του FontScheme του InheritedTheme.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Δεδομένα για αρχικοποίηση. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Αρχικοποιεί το FontScheme με νέο αντικείμενο για αντικατάσταση του FontScheme του InheritedTheme. Και αρχικοποιεί τα δεδομένα του νέου αντικειμένου με τα δεδομένα του FontScheme του InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Αρχικοποιεί το FormatScheme με νέο αντικείμενο για αντικατάσταση του FormatScheme του InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Αρχικοποιεί το FormatScheme με νέο αντικείμενο για αντικατάσταση του FormatScheme του InheritedTheme.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Δεδομένα για αρχικοποίηση. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Αρχικοποιεί το FormatScheme με νέο αντικείμενο για αντικατάσταση του FormatScheme του InheritedTheme. Και αρχικοποιεί τα δεδομένα του νέου αντικειμένου με τα δεδομένα του FormatScheme του InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Ορίζει το ColorScheme, FontScheme, FormatScheme σε null για να απενεργοποιήσει οποιαδήποτε αντικατάσταση με αυτό το αντικείμενο θέματος.