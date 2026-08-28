---
title: Audio
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/audio/
---
## Κλάση ήχου

 Απεικονίζει ένα ενσωματωμένο αρχείο ήχου.
 
### getBinaryData {#getBinaryData}

| Όνομα | Περιγραφή |
| --- | --- |
| getBinaryData () | Επιστρέφει το αντίγραφο των δεδομένων ενός ήχου. Σε περίπτωση μεγάλης ποσότητας δεδομένων, σκεφτείτε τη χρήση της μεθόδου #getStream για να αποφύγετε την περιττή φόρτωση των δεδομένων του ήχου στη μνήμη ή ακόμη και το OutOfMemoryException. Μόνο για ανάγνωση byte[]. |

 **Επιστρέφει:**
byte


---


### getContentType {#getContentType}

| Όνομα | Περιγραφή |
| --- | --- |
| getContentType () | Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο σε ( #getBinaryData). Μόνο για ανάγνωση String. |

 **Επιστρέφει:**
String


---


### getStream {#getStream}

| Όνομα | Περιγραφή |
| --- | --- |
| getStream () | Επιστρέφει ροή Stream για ανάγνωση. Χρησιμοποιήστε το 'using' ή κλείστε τη ροή μετά τη χρήση. |

 **Επιστρέφει:**
InputStream


---


### setContentType {#setContentType}

| Όνομα | Περιγραφή |
| --- | --- |
| setContentType (String) | Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο σε ( #getBinaryData). Μόνο για ανάγνωση String. |

 **Επιστρέφει:**
void


---