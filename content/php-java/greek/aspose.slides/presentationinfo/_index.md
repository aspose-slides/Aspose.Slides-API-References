---
title: PresentationInfo
second_title: Aspose.Sildes για PHP μέσω αναφοράς Java API
description: 
type: docs

url: /el/aspose.slides/presentationinfo/
---
## PresentationInfo κλάση

 Πληροφορίες για το αρχείο παρουσίασης

### checkPassword {#checkPassword}

| Όνομα | Περιγραφή |
| --- | --- |
| checkPassword (String) | Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για μια παρουσίαση που προστατεύεται με ανοιχτό κωδικό πρόσβασης. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | String | Ο password προς έλεγχο. Όταν το password είναι null ή κενό, αυτή η μέθοδος επιστρέφει false. |

 **Επιστροφή:**
boolean

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | NotSupportedException | εάν η μορφή δεν υποστηρίζεται για έλεγχο κωδικών πρόσβασης. |


---


### checkWriteProtection {#checkWriteProtection}

| Όνομα | Περιγραφή |
| --- | --- |
| checkWriteProtection (String) | Ελέγχει εάν ένας κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση που προστατεύεται από εγγραφή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | String | Ο password προς έλεγχο. 1. Πρέπει να ελέγξετε την ( #isWriteProtected) ιδιότητα πριν καλέσετε αυτή τη μέθοδο. 2. Όταν το password είναι null ή κενό, αυτή η μέθοδος επιστρέφει false. |

 **Επιστροφή:**
boolean

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | InvalidOperationException | Εάν μια παρουσίαση προστατεύεται με κωδικό για άνοιγμα ή η μορφή δεν υποστηρίζει προστασία εγγραφής |


---


### getLoadFormat {#getLoadFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getLoadFormat () | Παίρνει τη μορφή της συνδεδεμένης παρουσίασης. Μόνο για ανάγνωση LoadFormat. |

 **Επιστροφή:**
int


---


### isEncrypted {#isEncrypted}

| Όνομα | Περιγραφή |
| --- | --- |
| isEncrypted () | Επιστρέφει True εάν η συνδεδεμένη παρουσίαση είναι κρυπτογραφημένη, διαφορετικά False. Μόνο για ανάγνωση boolean. |

 **Επιστροφή:**
boolean


---


### isPasswordProtected {#isPasswordProtected}

| Όνομα | Περιγραφή |
| --- | --- |
| isPasswordProtected () | Παίρνει τιμή η οποία δείχνει εάν η συνδεδεμένη παρουσίαση προστατεύεται με κωδικό για άνοιγμα. |

 **Επιστροφή:**
boolean


---


### isWriteProtected {#isWriteProtected}

| Όνομα | Περιγραφή |
| --- | --- |
| isWriteProtected () | Παίρνει τιμή η οποία δείχνει εάν η συνδεδεμένη παρουσίαση είναι προστατευμένη από εγγραφή. Εάν η παρουσίαση προστατεύεται με κωδικό για άνοιγμα, η τιμή της ιδιότητας είναι NotDefined. |

 **Επιστροφή:**
byte


---


### readDocumentProperties {#readDocumentProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| readDocumentProperties () | Παίρνει τις ιδιότητες εγγράφου της συνδεδεμένης παρουσίασης. |

 **Επιστροφή:**
[DocumentProperties](../documentproperties)


---


### updateDocumentProperties {#updateDocumentProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| updateDocumentProperties ([DocumentProperties](../documentproperties)) | Ενημερώνει τις ιδιότητες της συνδεδεμένης παρουσίασης. |

 **Επιστροφή:**
void


---


### writeBindedPresentation {#writeBindedPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| writeBindedPresentation (OutputStream) | Γράφει τη συνδεδεμένη παρουσίαση σε ροή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | OutputStream | Η stream πρέπει να είναι seekable και writable. |

 **Επιστροφή:**
void


---


### writeBindedPresentation {#writeBindedPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| writeBindedPresentation (String) | Γράφει τη συνδεδεμένη παρουσίαση σε αρχείο. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | String | Αρχείο παρουσίασης. |

 **Επιστροφή:**
void


---