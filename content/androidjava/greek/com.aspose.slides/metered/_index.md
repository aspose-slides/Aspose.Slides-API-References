---
title: Metered
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Παρέχει μεθόδους για ορισμό του κλειδιού μετρητή.
type: docs
url: /el/com.aspose.slides/metered/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για ορισμό του κλειδιού μετρητή.
## Κατασκευαστές

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | Αρχικοποιεί ένα νέο αντικείμενο αυτής της κλάσης. |
## Μεθόδοι

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ορίζει το δημόσιο και το ιδιωτικό κλειδί του μετρητή. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Επιστρέφει το μέγεθος του αρχείου κατανάλωσης |
| [getConsumptionCredit()](#getConsumptionCredit--) | Επιστρέφει το πιστωτικό κατανάλωσης |
| [isMeteredLicensed()](#isMeteredLicensed--) | Ελέγχει εάν ο μετρητής είναι αδειοδοτημένος |
### Metered() {#Metered--}
```
public Metered()
```


Αρχικοποιεί ένα νέο αντικείμενο αυτής της κλάσης.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ορίζει το δημόσιο και το ιδιωτικό κλειδί του μετρητή. Εάν αγοράσετε αδειοδότηση μετρητή, κατά την εκκίνηση της εφαρμογής, αυτή η API πρέπει να κληθεί· συνήθως αυτό αρκεί. Ωστόσο, εάν αποτυγχάνει συνεχώς η αποστολή των δεδομένων κατανάλωσης και ξεπεραστούν οι 24 ώρες, η άδεια θα μεταβεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτή την περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτήν την API.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | δημόσιο κλειδί |
| privateKey | java.lang.String | ιδιωτικό κλειδί |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Επιστρέφει το μέγεθος του αρχείου κατανάλωσης

**Επιστρέφει:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Επιστρέφει το πιστωτικό κατανάλωσης

**Επιστρέφει:**
double - ποσότητα κατανάλωσης
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Ελέγχει εάν ο μετρητής είναι αδειοδοτημένος

**Επιστρέφει:**
boolean - Αληθές ή ψευδές