---
title: SensitivityLabelCollection
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/sensitivitylabelcollection/
---
## SensitivityLabelCollection κλάση

 Αντιπροσωπεύει μια συλλογή ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο.
 
### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (String, UUID, boolean, int) | Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | String | Το id της ετικέτας ευαισθησίας. |
| siteId | UUID | Το αναγνωριστικό του site του Azure Active Directory (Azure AD). |
| isEnabled | boolean | Σημαία που υποδεικνύει εάν η ετικέτα ευαισθησίας είναι ενεργοποιημένη. |
| methodType | int | Η μέθοδος ανάθεσης για την ετικέτα ευαισθησίας. |

 **Επιστροφή:**
[SensitivityLabel](../sensitivitylabel)


---

### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add ([SensitivityLabel](../sensitivitylabel)) | Προσθέτει ένα SensitivityLabel στη συλλογή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | [SensitivityLabel](../sensitivitylabel) | Το αντικείμενο SensitivityLabel που θα προστεθεί στο τέλος της συλλογής. |

 **Επιστροφή:**
int

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Thrown when the sensitivity label with the same Id has already been added. |


---

### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |

 **Επιστροφή:**
void


---

### copyTo {#copyTo}

| Όνομα | Περιγραφή |
| --- | --- |
| copyTo (com.aspose.slides.ISensitivityLabel[], int) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.slides.ISensitivityLabel[] | Πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα προορισμού. |

 **Επιστροφή:**
void


---

### getCount {#getCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getCount () | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Μόνο για ανάγνωση int. |

 **Επιστροφή:**
int


---

### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Επιστρέφει την ετικέτα ευαισθησίας με βάση τον δείκτη. |

 **Επιστροφή:**
[SensitivityLabel](../sensitivitylabel)


---

### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Επιστρέφει έναν enumerator που διασχίζει τη συλλογή. |

 **Επιστροφή:**



---

### removeAt {#removeAt}

| Όνομα | Περιγραφή |
| --- | --- |
| removeAt (int) | Αφαιρεί την ετικέτα ευαισθησίας στο καθορισμένο δείκτη. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της ετικέτας ευαισθησίας που πρέπει να διαγραφεί. |

 **Επιστροφή:**
void


---