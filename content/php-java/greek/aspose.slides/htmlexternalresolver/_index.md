---
title: HtmlExternalResolver
second_title: Aspose.Sildes για PHP μέσω Java API Reference
description: 
type: docs
url: /el/aspose.slides/htmlexternalresolver/
---
## HtmlExternalResolver κλάση

Αντικείμενο κλήσης που χρησιμοποιείται από τη ρουτίνα εισαγωγής HTML για την απόκτηση αναφερόμενων αντικειμένων όπως εικόνες. Η χρήση αυτού του resolver μπορεί να δημιουργήσει ευπάθεια όταν το αρχείο HTML που παρέχεται από τον πελάτη επιτρέπει στο λογισμικό του διακομιστή να αποκτήσει τοπικό ή δικτυακό αρχείο. Χρησιμοποιήστε το με προσοχή. Συνιστάται να μην καθορίζετε καθόλου το HtmlExternalResolver (θα διαβαστούν μόνο ενσωματωμένα αντικείμενα) ή να δημιουργήσετε κάποια υποκατηγορία που ελέγχει αν το καθορισμένο uri είναι έγκυρο.
### HtmlExternalResolver {#HtmlExternalResolver}

| Όνομα | Περιγραφή |
| --- | --- |
| HtmlExternalResolver() |  |

**Επιστρέφει:**
HtmlExternalResolver


---


### getEntity {#getEntity}

| Όνομα | Περιγραφή |
| --- | --- |
| getEntity (String) | Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο. |

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
| resolveUri (String, String) | Εξακονίζει το απόλυτο URI από τα βασικά και σχετικά URIs. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | String | Βασικό URI των αντικειμένων που συνδέουν |
| relativeUri | String | Σχετικό URI προς το συνδεδεμένο αντικείμενο. |

**Επιστρέφει:**
String


---