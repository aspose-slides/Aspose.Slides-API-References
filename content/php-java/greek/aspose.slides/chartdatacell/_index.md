---
title: ChartDataCell
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/chartdatacell/
---
## ChartDataCell κλάση

Αντιπροσωπεύει το κελί για δεδομένα διαγράμματος.

### calculate {#calculate}

| Όνομα | Περιγραφή |
| --- | --- |
| calculate (boolean) | Εάν το κελί περιέχει τύπο, η τιμή θα ενημερωθεί βάσει αυτού του τύπου. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| updateValues | boolean | Αν είναι false, δεν θα γίνει πραγματικός υπολογισμός. Χρησιμοποιήστε true για έλεγχο πιθανών εξαιρέσεων. |

**Επιστρέφει:**
void


---


### getChartDataWorksheet {#getChartDataWorksheet}

| Όνομα | Περιγραφή |
| --- | --- |
| getChartDataWorksheet () | Λαμβάνει το φύλλο εργασίας. Μόνη για ανάγνωση IChartDataWorksheet. |

**Επιστρέφει:**
[ChartDataWorksheet](../chartdataworksheet)


---


### getColumn {#getColumn}

| Όνομα | Περιγραφή |
| --- | --- |
| getColumn () | Επιστρέφει τον δείκτη της στήλης του φύλλου εργασίας στο οποίο βρίσκεται το κελί. Μόνη για ανάγνωση int. |

**Επιστρέφει:**
int


---


### getCustomNumberFormat {#getCustomNumberFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getCustomNumberFormat () | Λαμβάνει ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Εάν η τιμή είναι κενή, θα χρησιμοποιηθεί η τιμή PresetNumberFormat. Αναγνώσιμη/εγγράψιμη String. |

**Επιστρέφει:**
String

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentNullException | Συμβαίνει εάν η τιμή είναι null. |


---


### getFormula {#getFormula}

| Όνομα | Περιγραφή |
| --- | --- |
| getFormula () | Λαμβάνει ή ορίζει τον τύπο σε μορφή A1. |

**Επιστρέφει:**
String


---


### getPresetNumberFormat {#getPresetNumberFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresetNumberFormat () | Λαμβάνει ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Ο προεπιλεγμένος αριθμός πρέπει να βρίσκεται στο [0..22] ή [37..49]. Αναγνώσιμη/εγγράψιμη byte. |

**Επιστρέφει:**
byte


---


### getR1C1Formula {#getR1C1Formula}

| Όνομα | Περιγραφή |
| --- | --- |
| getR1C1Formula () | Λαμβάνει ή ορίζει τον τύπο σε μορφή R1C1. |

**Επιστρέφει:**
String


---


### getRow {#getRow}

| Όνομα | Περιγραφή |
| --- | --- |
| getRow () | Επιστρέφει τον δείκτη της γραμμής του φύλλου εργασίας στο οποίο βρίσκεται το κελί. Μόνη για ανάγνωση int. |

**Επιστρέφει:**
int


---


### getValue {#getValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getValue () | Λαμβάνει ή ορίζει την τιμή ενός κελιού. Αναγνώσιμη/εγγράψιμη Object. |

**Επιστρέφει:**
Object


---


### isHidden {#isHidden}

| Όνομα | Περιγραφή |
| --- | --- |
| isHidden () | Καθορίζει αν το κελί είναι κρυφό. Μόνη για ανάγνωση boolean. |

**Επιστρέφει:**
boolean


---


### setCustomNumberFormat {#setCustomNumberFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setCustomNumberFormat (String) | Λαμβάνει ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Εάν η τιμή είναι κενή, θα χρησιμοποιηθεί η τιμή PresetNumberFormat. Αναγνώσιμη/εγγράψιμη String. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentNullException | Συμβαίνει εάν η τιμή είναι null. |


---


### setFormula {#setFormula}

| Όνομα | Περιγραφή |
| --- | --- |
| setFormula (String) | Λαμβάνει ή ορίζει τον τύπο σε μορφή A1. |

**Επιστρέφει:**
void


---


### setPresetNumberFormat {#setPresetNumberFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setPresetNumberFormat (byte) | Λαμβάνει ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Ο προεπιλεγμένος αριθμός πρέπει να βρίσκεται στο [0..22] ή [37..49]. Αναγνώσιμη/εγγράψιμη byte. |

**Επιστρέφει:**
void


---


### setR1C1Formula {#setR1C1Formula}

| Όνομα | Περιγραφή |
| --- | --- |
| setR1C1Formula (String) | Λαμβάνει ή ορίζει τον τύπο σε μορφή R1C1. |

**Επιστρέφει:**
void


---


### setValue {#setValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setValue (Object) | Λαμβάνει ή ορίζει την τιμή ενός κελιού. Αναγνώσιμη/εγγράψιμη Object. |

**Επιστρέφει:**
void


---