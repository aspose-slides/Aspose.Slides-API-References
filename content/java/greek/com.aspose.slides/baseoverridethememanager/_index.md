---
title: BaseOverrideThemeManager
second_title: Aspose.Slides για την Java API Αναφορά
description: Βασική κλάση για κλάσεις που παρέχουν πρόσβαση σε διαφορετικούς τύπους τροποποιημένων θεμάτων.
type: docs
url: /el/com.aspose.slides/baseoverridethememanager/
---
**Κληρονόμηση:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Βασική κλάση για κλάσεις που παρέχουν πρόσβαση σε διαφορετικούς τύπους τροποποιημένων θεμάτων.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Επιστρέφει το αντικείμενο του overriding theme. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Επιστρέφει το αντικείμενο του overriding theme. |
| [createThemeEffective()](#createThemeEffective--) | Επιστρέφει το αντικείμενο του theme. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Καθορίζει αν το OverrideTheme υπερκαλύπτει το κληρονομημένο αποτελεσματικό theme ή όχι. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Εφαρμόζει επιπλέον χρωματικό σχήμα σε μια διαφάνεια. |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Επιστρέφει το αντικείμενο του overriding theme. Ανάγνωση/εγγραφή [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Επιστρέφει:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Επιστρέφει το αντικείμενο του overriding theme. Ανάγνωση/εγγραφή [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Επιστρέφει το αντικείμενο του theme.

**Επιστρέφει:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Καθορίζει αν το OverrideTheme υπερκαλύπτει το κληρονομημένο αποτελεσματικό theme ή όχι. Για να ενεργοποιήσετε το OverrideTheme για υπερκαλύψη, χρησιμοποιήστε τις μεθόδους OverrideTheme.Init*(). Για να το απενεργοποιήσετε, χρησιμοποιήστε τη μέθοδο OverrideTheme.Clear(). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**  
boolean

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Εφαρμόζει επιπλέον χρωματικό σχήμα σε μια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Το αντικείμενο [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |