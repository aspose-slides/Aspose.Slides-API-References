---
title: BaseOverrideThemeManager
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Βασική κλάση για κλάσεις που παρέχουν πρόσβαση σε διαφορετικούς τύπους παρακαμφθέντων θεμάτων.
type: docs
url: /el/com.aspose.slides/baseoverridethememanager/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Βασική κλάση για κλάσεις που παρέχουν πρόσβαση σε διαφορετικούς τύπους παρακαμφθέντων θεμάτων.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Επιστρέφει το αντικείμενο του παρακάμπτοντος θέματος. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Επιστρέφει το αντικείμενο του παρακάμπτοντος θέματος. |
| [createThemeEffective()](#createThemeEffective--) | Επιστρέφει το αντικείμενο του θέματος. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Καθορίζει αν το OverrideTheme παρακάμπτει το κληρονομημένο αποτελεσματικό θέμα ή όχι. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Εφαρμόζει πρόσθετο σχήμα χρώματος σε μια διαφάνεια. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Επιστρέφει το αντικείμενο του παρακάμπτοντος θέματος. Ανάγνωση/εγγραφή [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Επιστρέφει:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Επιστρέφει το αντικείμενο του παρακάμπτοντος θέματος. Ανάγνωση/εγγραφή [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Επιστρέφει το αντικείμενο του θέματος.

**Επιστρέφει:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Καθορίζει αν το OverrideTheme παρακάμπτει το κληρονομημένο αποτελεσματικό θέμα ή όχι. Για ενεργοποίηση του OverrideTheme για παράκαμψη χρησιμοποιήστε τις μεθόδους OverrideTheme.Init*(). Για απενεργοποίηση του OverrideTheme από την παράκαμψη χρησιμοποιήστε τη μέθοδο OverrideTheme.Clear(). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Εφαρμόζει πρόσθετο σχήμα χρώματος σε μια διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Το αντικείμενο [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |