---
title: OleObjectFrame
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/oleobjectframe/
---
## OleObjectFrame κλάση

 Αντιπροσωπεύει ένα αντικείμενο OLE σε μία διαφάνεια.
 
### getEmbeddedData {#getEmbeddedData}

| Όνομα | Περιγραφή |
| --- | --- |
| getEmbeddedData () | Λαμβάνει ή ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Ανάγνωση/Εγγραφή IOleEmbeddedDataInfo. |

 **Επιστρέφει:**
[OleEmbeddedDataInfo](../oleembeddeddatainfo)


---


### getEmbeddedFileLabel {#getEmbeddedFileLabel}

| Όνομα | Περιγραφή |
| --- | --- |
| getEmbeddedFileLabel () | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |

 **Επιστρέφει:**
String


---


### getEmbeddedFileName {#getEmbeddedFileName}

| Όνομα | Περιγραφή |
| --- | --- |
| getEmbeddedFileName () | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |

 **Επιστρέφει:**
String


---


### getLinkFileName {#getLinkFileName}

| Όνομα | Περιγραφή |
| --- | --- |
| getLinkFileName () | Επιστρέφει την πλήρη διαδρομή προς ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το σύντομο όνομα αρχείου. Μόνο ανάγνωση String. |

 **Επιστρέφει:**
String


---


### getLinkPathLong {#getLinkPathLong}

| Όνομα | Περιγραφή |
| --- | --- |
| getLinkPathLong () | Επιστρέφει την πλήρη διαδρομή προς ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
String


---


### getLinkPathRelative {#getLinkPathRelative}

| Όνομα | Περιγραφή |
| --- | --- |
| getLinkPathRelative () | Επιστρέφει τη σχετική διαδρομή προς ένα συνδεδεμένο αρχείο εάν υπάρχει, αλλιώς επιστρέφει κενό string. Μόνο ανάγνωση String. Στις παρουσιάσεις Ppt, ορισμένοι σύνδεσμοι αντικειμένων Ole ενδέχεται να έχουν σχετική αναπαράσταση. |

 **Επιστρέφει:**
String


---


### getObjectName {#getObjectName}

| Όνομα | Περιγραφή |
| --- | --- |
| getObjectName () | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
String


---


### getObjectProgId {#getObjectProgId}

| Όνομα | Περιγραφή |
| --- | --- |
| getObjectProgId () | Επιστρέφει το ProgID ενός αντικειμένου. Μόνο ανάγνωση String. |

 **Επιστρέφει:**
String


---


### getSubstitutePictureFormat {#getSubstitutePictureFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getSubstitutePictureFormat () | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. Μόνο ανάγνωση IPictureFillFormat. |

 **Επιστρέφει:**
[PictureFillFormat](../picturefillformat)


---


### getSubstitutePictureTitle {#getSubstitutePictureTitle}

| Όνομα | Περιγραφή |
| --- | --- |
| getSubstitutePictureTitle () | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. Ανάγνωση/Εγγραφή String. Όταν IsObjectIcon == false αυτή η τιμή αγνοείται. Το string μπορεί να περικοπεί ανάλογα με το μέγεθος του εικονιδίου Ole. |

 **Επιστρέφει:**
String


---


### getUpdateAutomatic {#getUpdateAutomatic}

| Όνομα | Περιγραφή |
| --- | --- |
| getUpdateAutomatic () | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοιχτεί ή εκτυπωθεί. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isObjectIcon {#isObjectIcon}

| Όνομα | Περιγραφή |
| --- | --- |
| isObjectIcon () | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isObjectLink {#isObjectLink}

| Όνομα | Περιγραφή |
| --- | --- |
| isObjectLink () | Καθορίζει εάν ένα αντικείμενο είναι συνδεδεμένο σε εξωτερικό αρχείο. Μόνο ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### setEmbeddedData {#setEmbeddedData}

| Όνομα | Περιγραφή |
| --- | --- |
| setEmbeddedData ([OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| embeddedData | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | Ενσωματωμένα δεδομένα IOleEmbeddedDataInfo. Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντανακλούν τα νέα δεδομένα και ορίζει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentNullException | Όταν η παράμετρος embeddedData είναι null. |


---


### setLinkPathLong {#setLinkPathLong}

| Όνομα | Περιγραφή |
| --- | --- |
| setLinkPathLong (String) | Επιστρέφει την πλήρη διαδρομή προς ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
void


---


### setObjectIcon {#setObjectIcon}

| Όνομα | Περιγραφή |
| --- | --- |
| setObjectIcon (boolean) | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setObjectName {#setObjectName}

| Όνομα | Περιγραφή |
| --- | --- |
| setObjectName (String) | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. Ανάγνωση/Εγγραφή String. |

 **Επιστρέφει:**
void


---


### setObjectProgId {#setObjectProgId}

| Όνομα | Περιγραφή |
| --- | --- |
| setObjectProgId (String) | Επιστρέφει το ProgID ενός αντικειμένου. Μόνο ανάγνωση String. |

 **Επιστρέφει:**
void


---


### setSubstitutePictureTitle {#setSubstitutePictureTitle}

| Όνομα | Περιγραφή |
| --- | --- |
| setSubstitutePictureTitle (String) | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. Ανάγνωση/Εγγραφή String. Όταν IsObjectIcon == false αυτή η τιμή αγνοείται. Το string μπορεί να περικοπεί ανάλογα με το μέγεθος του εικονιδίου Ole. |

 **Επιστρέφει:**
void


---


### setUpdateAutomatic {#setUpdateAutomatic}

| Όνομα | Περιγραφή |
| --- | --- |
| setUpdateAutomatic (boolean) | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοιχτεί ή εκτυπωθεί. Ανάγνωση/Εγγραφή boolean. |

 **Επιστρέφει:**
void


---