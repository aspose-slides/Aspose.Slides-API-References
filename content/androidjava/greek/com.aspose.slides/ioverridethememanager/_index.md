---
title: IOverrideThemeManager
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Παρέχει πρόσβαση σε διαφορετικούς τύπους παραμετροποιημένων θεμάτων.
type: docs
url: /el/com.aspose.slides/ioverridethememanager/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Παρέχει πρόσβαση σε διαφορετικούς τύπους παραμετροποιημένων θεμάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Καθορίζει εάν το OverrideTheme αντικαθιστά το κληρονομικό ενεργό θέμα ή όχι. |
| [getOverrideTheme()](#getOverrideTheme--) | Επιστρέφει το αντικείμενο του αντικαθιστώντος θέματος. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Επιστρέφει το αντικείμενο του αντικαθιστώντος θέματος. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Καθορίζει εάν το OverrideTheme αντικαθιστά το κληρονομικό ενεργό θέμα ή όχι. Για να ενεργοποιήσετε το OverrideTheme για αντικατάσταση, χρησιμοποιήστε τις μεθόδους OverrideTheme.Init\*(). Για να απενεργοποιήσετε το OverrideTheme από την αντικατάσταση, χρησιμοποιήστε τη μέθοδο OverrideTheme.Clear(). Boolean μόνο για ανάγνωση.

**Επιστρέφει:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Επιστρέφει το αντικείμενο του αντικαθιστώντος θέματος. Ανάγνωση/εγγραφή [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Επιστρέφει:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Επιστρέφει το αντικείμενο του αντικαθιστώντος θέματος. Ανάγνωση/εγγραφή [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |