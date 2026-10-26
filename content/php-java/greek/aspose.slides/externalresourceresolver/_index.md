---
title: ExternalResourceResolver
second_title: Aspose.Sildes για PHP μέσω Αναφοράς API Java
description: 
type: docs
url: /el/aspose.slides/externalresourceresolver/
---
## ExternalResourceResolver κλάση

 Κλάση Callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html, Svg. Η χρήση αυτού του resolver μπορεί να δημιουργήσει ευπάθεια όταν ένα αρχείο HTML ή SVG που παρέχεται από τον πελάτη επιτρέπει στο λογισμικό διακομιστή να αποκτήσει τοπικό ή δικτυακό αρχείο. Χρησιμοποιήστε με προσοχή. Συνιστάται να μην καθορίζετε το ExternalResourceResolver καθόλου (μόνο ενσωματωμένα αντικείμενα θα διαβαστούν) ή να δημιουργήσετε κάποια υποκατηγορία η οποία ελέγχει αν το καθορισμένο uri είναι έγκυρο.
### ExternalResourceResolver {#ExternalResourceResolver}

| Όνομα | Περιγραφή |
| --- | --- |
| ExternalResourceResolver() |  |

 **Επιστρέφει:**
ExternalResourceResolver


---


### getEntity {#getEntity}

| Όνομα | Περιγραφή |
| --- | --- |
| getEntity (String) | Χαρτογραφεί ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | String | Απόλυτο URI προς το αντικείμενο. |

 **Επιστρέφει:**
InputStream


---


### resolveUri {#resolveUri}

| Όνομα | Περιγραφή |
| --- | --- |
| resolveUri (String, String) | Επιδιόρθωση του απόλυτου URI από τα βασικά και σχετικά URIs. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | String | Βασικό URI των συνδεδεμένων αντικειμένων |
| relativeUri | String | Σχετικό URI προς το συνδεδεμένο αντικείμενο. |

 **Επιστρέφει:**
String


---