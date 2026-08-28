---
title: ProtectionManager
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/protectionmanager/
---
## ProtectionManager κλάση

Διαχείριση προστασίας παρουσίασης με κωδικό πρόσβασης.

### checkWriteProtection {#checkWriteProtection}

| Όνομα | Περιγραφή |
| --- | --- |
| checkWriteProtection (String) | Καθορίζει αν μια παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για τροποποίηση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | String | Ο κωδικός πρόσβασης για έλεγχο. 1. Πρέπει να ελέγξετε την ιδιότητα ( #isWriteProtected) πριν καλέσετε αυτή τη μέθοδο. 2. Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. |

**Επιστρέφει:**
boolean


---

### encrypt {#encrypt}

| Όνομα | Περιγραφή |
| --- | --- |
| encrypt (String) | Κρυπτογραφεί την παρουσίαση με συγκεκριμένο κωδικό πρόσβασης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| encryptionPassword | String | Ο κωδικός πρόσβασης. |

**Επιστρέφει:**
void


---

### getEncryptDocumentProperties {#getEncryptDocumentProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getEncryptDocumentProperties () | Αυτή η ιδιότητα έχει νόημα, εάν η παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης. Εάν είναι true, τότε οι ιδιότητες εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν είναι false, τότε οι ιδιότητες εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean


---

### getEncryptionPassword {#getEncryptionPassword}

| Όνομα | Περιγραφή |
| --- | --- |
| getEncryptionPassword () | Λαμβάνει τον κωδικό πρόσβασης που χρησιμοποιείται για την κρυπτογράφηση της παρουσίασης. Μόνο ανάγνωση String. |

**Επιστρέφει:**
String


---

### getReadOnlyRecommended {#getReadOnlyRecommended}

| Όνομα | Περιγραφή |
| --- | --- |
| getReadOnlyRecommended () | Λαμβάνει ή ορίζει την πρόταση μόνο ανάγνωσης. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean


---

### isEncrypted {#isEncrypted}

| Όνομα | Περιγραφή |
| --- | --- |
| isEncrypted () | Λαμβάνει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι κρυπτογραφημένη. Μόνο ανάγνωση boolean. Τιμή: true εάν η παρουσίαση φορτώθηκε από κρυπτογραφημένο αρχείο ή κλήθηκε η μέθοδος #encrypt(String) ; διαφορετικά, false. |

**Επιστρέφει:**
boolean


---

### isOnlyDocumentPropertiesLoaded {#isOnlyDocumentPropertiesLoaded}

| Όνομα | Περιγραφή |
| --- | --- |
| isOnlyDocumentPropertiesLoaded () | Αυτή η ιδιότητα έχει νόημα, εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες. Τιμή true σημαίνει ότι μόνο οι ιδιότητες εγγράφου φορτώνονται από ένα κρυπτογραφημένο αρχείο παρουσίασης χωρίς χρήση κωδικού πρόσβασης. Τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση φορτώνεται με χρήση του σωστού κωδικού πρόσβασης, όχι μόνο οι ιδιότητες εγγράφου φορτώνονται. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας είναι πάντα false. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, η τιμή της ιδιότητας είναι πάντα false. Εάν Presentation.EncryptDocumentProperties είναι true, τότε η τιμή της ιδιότητας IsOnlyDocumentPropertiesLoaded είναι πάντα false. Μόνο ανάγνωση boolean. |

**Επιστρέφει:**
boolean


---

### isWriteProtected {#isWriteProtected}

| Όνομα | Περιγραφή |
| --- | --- |
| isWriteProtected () | Λαμβάνει μια τιμή που υποδεικνύει αν αυτή η παρουσίαση είναι προστατευμένη από εγγραφή. Μόνο ανάγνωση boolean. |

**Επιστρέφει:**
boolean


---

### removeEncryption {#removeEncryption}

| Όνομα | Περιγραφή |
| --- | --- |
| removeEncryption () | Αφαιρεί την κρυπτογράφηση. |

**Επιστρέφει:**
void


---

### removeWriteProtection {#removeWriteProtection}

| Όνομα | Περιγραφή |
| --- | --- |
| removeWriteProtection () | Αφαιρεί την προστασία εγγραφής για αυτή την παρουσίαση. |

**Επιστρέφει:**
void


---

### setEncryptDocumentProperties {#setEncryptDocumentProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| setEncryptDocumentProperties (boolean) | Αυτή η ιδιότητα έχει νόημα, εάν η παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης. Εάν είναι true, τότε οι ιδιότητες εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν είναι false, τότε οι ιδιότητες εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void


---

### setReadOnlyRecommended {#setReadOnlyRecommended}

| Όνομα | Περιγραφή |
| --- | --- |
| setReadOnlyRecommended (boolean) | Λαμβάνει ή ορίζει την πρόταση μόνο ανάγνωσης. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void


---

### setWriteProtection {#setWriteProtection}

| Όνομα | Περιγραφή |
| --- | --- |
| setWriteProtection (String) | Ορίζει την προστασία εγγραφής για αυτή την παρουσίαση με συγκεκριμένο κωδικό πρόσβασης. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | String | Ο κωδικός πρόσβασης. |

**Επιστρέφει:**
void


---