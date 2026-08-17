---
title: Metered
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει μεθόδους για τον ορισμό του κλειδιού metered.
type: docs
url: /el/com.aspose.slides/metered/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για τον ορισμό του κλειδιού metered.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ορίζει το δημόσιο και ιδιωτικό κλειδί metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Λαμβάνει το μέγεθος του αρχείου κατανάλωσης |
| [getConsumptionCredit()](#getConsumptionCredit--) | Λαμβάνει την πίστωση κατανάλωσης |
| [isMeteredLicensed()](#isMeteredLicensed--) | Ελέγχει εάν το metered είναι αδειοδοτημένο |
### Metered() {#Metered--}
```
public Metered()
```


Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ορίζει το δημόσιο και ιδιωτικό κλειδί metered. Εάν αγοράσετε άδεια metered, όταν ξεκινάει η εφαρμογή, θα πρέπει να κληθεί αυτό το API, κατά κανόνα αρκεί. Ωστόσο, εάν αποτυγχάνει συνεχώς η ανεβάθμιση δεδομένων κατανάλωσης και ξεπεραστούν οι 24 ώρες, η άδεια θα μεταβεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτήν την περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | java.lang.String | δημόσιο κλειδί |
| privateKey | java.lang.String | ιδιωτικό κλειδί |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Λαμβάνει το μέγεθος του αρχείου κατανάλωσης

**Επιστρέφει:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Λαμβάνει την πίστωση κατανάλωσης

**Επιστρέφει:**
double - ποσότητα κατανάλωσης
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Ελέγχει εάν το metered είναι αδειοδοτημένο

**Επιστρέφει:**
boolean - αληθές ή ψευδές