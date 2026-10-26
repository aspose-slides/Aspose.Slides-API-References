---
title: DigitalSignature
second_title: Aspose.Sildes για PHP μέσω αναφοράς Java API
description: 
type: docs

url: /el/aspose.slides/digitalsignature/
---
## DigitalSignature κλάση

 Ψηφιακή υπογραφή σε υπογεγραμμένο αρχείο.
 
### DigitalSignature {#DigitalSignature}

| Όνομα | Περιγραφή |
| --- | --- |
| DigitalSignature(byte[], String) | Δημιουργεί ένα νέο αντικείμενο DigitalSignature με το καθορισμένο πιστοποιητικό. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| certData | byte[] | ένας πίνακας byte που περιέχει το πιστοποιητικό |
| password | String | Κωδικός πρόσβασης που απαιτείται για την πρόσβαση στο πιστοποιητικό. |

 **Επιστρέφει:**
DigitalSignature


---


### DigitalSignature {#DigitalSignature}

| Όνομα | Περιγραφή |
| --- | --- |
| DigitalSignature(String, String) | Δημιουργεί ένα νέο αντικείμενο DigitalSignature με το καθορισμένο μονοπάτι αρχείου πιστοποιητικού και κωδικό πρόσβασης. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Διαδρομή προς το αρχείο με το πιστοποιητικό. |
| password | String | Κωδικός πρόσβασης που απαιτείται για την πρόσβαση στο πιστοποιητικό. |

 **Επιστρέφει:**
DigitalSignature


---


### getCertificate {#getCertificate}

| Όνομα | Περιγραφή |
| --- | --- |
| getCertificate () | Αντικείμενο πιστοποιητικού που χρησιμοποιήθηκε για την υπογραφή του εγγράφου. Μόνο ανάγνωση byte[]. |

 **Επιστρέφει:**
byte


---


### getComments {#getComments}

| Όνομα | Περιγραφή |
| --- | --- |
| getComments () | Ο σκοπός της υπογραφής. Ανάγνωση/εγγραφή String. |

 **Επιστρέφει:**
String


---


### getSignTime {#getSignTime}

| Όνομα | Περιγραφή |
| --- | --- |
| getSignTime () | Ο χρόνος που υπεγράφη το έγγραφο. Μόνο ανάγνωση java.util.Date. |

 **Επιστρέφει:**
Date


---


### isValid {#isValid}

| Όνομα | Περιγραφή |
| --- | --- |
| isValid () | Εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί, η τιμή αυτή θα είναι true. Μόνο ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### setComments {#setComments}

| Όνομα | Περιγραφή |
| --- | --- |
| setComments (String) | Ο σκοπός της υπογραφής. Ανάγνωση/εγγραφή String. |

 **Επιστρέφει:**
void