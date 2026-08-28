---
title: Video
second_title: Aspose.Sildes για PHP μέσω Αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/video/
---
## Κλάση Video

Αντιπροσωπεύει μια εικόνα ενσωματωμένη σε μια παρουσίαση.

### getBinaryData {#getBinaryData}

| Όνομα | Περιγραφή |
| --- | --- |
| getBinaryData () | Επιστρέφει ένα αντίγραφο των δεδομένων ήχου. Σε περίπτωση μεγάλης ποσότητας δεδομένων, σκεφτείτε τη χρήση της #getStream μεθόδου για την αποφυγή περιττής φόρτωσης των δεδομένων του βίντεο στη μνήμη ή ακόμη της OutOfMemoryException. Μόνο ανάγνωση byte[]. |

**Επιστρέφει:**
byte


---


### getContentType {#getContentType}

| Όνομα | Περιγραφή |
| --- | --- |
| getContentType () | Επιστρέφει έναν τύπο MIME ενός βίντεο, κωδικοποιημένο σε ( #getBinaryData). Μόνο ανάγνωση String. |

**Επιστρέφει:**
String


---


### getStream {#getStream}

| Όνομα | Περιγραφή |
| --- | --- |
| getStream () | Επιστρέφει ροή Stream για ανάγνωση. Χρησιμοποιήστε 'using' ή κλείστε τη ροή μετά τη χρήση. |

**Επιστρέφει:**
InputStream


---