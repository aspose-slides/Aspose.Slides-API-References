---
title: Metered
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description:
type: docs

url: /el/aspose.slides/metered/
---
## Τάξη Metered
Παρέχει μεθόδους για τον ορισμό του κλειδιού metered.

### Metered {#Metered}

| Όνομα | Περιγραφή |
| --- | --- |
| Metered() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

**Επιστρέφει:**
Metered

---

### getConsumptionCredit {#getConsumptionCredit}

| Όνομα | Περιγραφή |
| --- | --- |
| getConsumptionCredit () | Λαμβάνει το πιστωτικό κατανάλωσης |

**Επιστρέφει:**
double

---

### getConsumptionQuantity {#getConsumptionQuantity}

| Όνομα | Περιγραφή |
| --- | --- |
| getConsumptionQuantity () | Λαμβάνει το μέγεθος του αρχείου κατανάλωσης |

**Επιστρέφει:**
double

---

### isMeteredLicensed {#isMeteredLicensed}

| Όνομα | Περιγραφή |
| --- | --- |
| isMeteredLicensed () | Ελέγχει εάν το metered είναι αδειοδοτημένο |

**Επιστρέφει:**
boolean

---

### setMeteredKey {#setMeteredKey}

| Όνομα | Περιγραφή |
| --- | --- |
| setMeteredKey (String, String) | Ορίζει το δημόσιο και το ιδιωτικό κλειδί metered. Αν αγοράσετε άδεια metered, όταν ξεκινά η εφαρμογή, αυτό το API πρέπει να κληθεί· συνήθως αυτό είναι αρκετό. Ωστόσο, εάν αποτυγχάνει συνεχόμενα η μεταφόρτωση δεδομένων κατανάλωσης και υπερβαίνει τις 24 ώρες, η άδεια θα μεταφερθεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτή την περίπτωση, ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | String | δημόσιο κλειδί |
| privateKey | String | ιδιωτικό κλειδί |

**Επιστρέφει:**
void

---