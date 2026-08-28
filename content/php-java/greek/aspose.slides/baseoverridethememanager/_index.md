---
title: BaseOverrideThemeManager
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/baseoverridethememanager/
---
## BaseOverrideThemeManager κλάση

 Βασική κλάση για κλάσεις που παρέχουν πρόσβαση σε διαφορετικούς τύπους αντικατασταμένων θεμάτων.
 
### applyColorScheme {#applyColorScheme}

| Όνομα | Περιγραφή |
| --- | --- |
| applyColorScheme ([ExtraColorScheme](../extracolorscheme)) | Εφαρμόζει επιπρόσθετο σχήμα χρωμάτων σε μια διαφάνεια. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| scheme | [ExtraColorScheme](../extracolorscheme) | Το αντικείμενο IExtraColorScheme. |

 **Επιστρέφει:**
void


---


### createThemeEffective {#createThemeEffective}

| Όνομα | Περιγραφή |
| --- | --- |
| createThemeEffective () | Επιστρέφει το αντικείμενο θέματος. |

 **Επιστρέφει:**
ThemeEffectiveData


---


### getOverrideTheme {#getOverrideTheme}

| Όνομα | Περιγραφή |
| --- | --- |
| getOverrideTheme () | Επιστρέφει το αντικείμενο του παρακάμπτοντος θέματος. Ανάγνωση/εγγραφή IOverrideTheme. |

 **Επιστρέφει:**
[OverrideTheme](../overridetheme)


---


### isOverrideThemeEnabled {#isOverrideThemeEnabled}

| Όνομα | Περιγραφή |
| --- | --- |
| isOverrideThemeEnabled () | Καθορίζει εάν το OverrideTheme αντικαθιστά το κληρονομικό αποτελεσματικό θέμα ή όχι. Για να ενεργοποιήσετε το OverrideTheme για αντικατάσταση, χρησιμοποιήστε τις μεθόδους OverrideTheme.Init*(). Για να απενεργοποιήσετε το OverrideTheme από την αντικατάσταση, χρησιμοποιήστε τη μέθοδο OverrideTheme.Clear(). Μόνο για ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### setOverrideTheme {#setOverrideTheme}

| Όνομα | Περιγραφή |
| --- | --- |
| setOverrideTheme ([OverrideTheme](../overridetheme)) | Επιστρέφει το αντικείμενο του παρακάμπτοντος θέματος. Ανάγνωση/εγγραφή IOverrideTheme. |

 **Επιστρέφει:**
void


---