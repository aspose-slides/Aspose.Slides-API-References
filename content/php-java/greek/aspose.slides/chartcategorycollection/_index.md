---
title: ChartCategoryCollection
second_title: Aspose.Sildes για PHP μέσω αναφοράς Java API
description: 
type: docs

url: /el/aspose.slides/chartcategorycollection/
---
## ChartCategoryCollection κλάση

 Αναπαριστά τη συλλογή των ChartCategory
 
### add {#add}

| Name | Description |
| --- | --- |
| add ([ChartDataCell](../chartdatacell)) | Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά δημιουργεί νέα κατηγορία διαγράμματος από IChartDataCell και την προσθέτει στη συλλογή. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| chartDataCell | [ChartDataCell](../chartdatacell) | Κελί που χρησιμοποιείται για τη δημιουργία της κατηγορίας διαγράμματος. |

 **Επιστρέφει:**
[ChartCategory](../chartcategory)

---

### add {#add}

| Name | Description |
| --- | --- |
| add (Object) | Δημιουργεί νέα ChartCategory από τιμή και την προσθέτει στη συλλογή. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| value | Object | Η τιμή. Αυτή η μέθοδος προσθέτει ένα φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιήσετε το ChartDataWorkbook για να προσθέσετε ή να επεξεργαστείτε τιμές κελιών, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680 |

 **Επιστρέφει:**
[ChartCategory](../chartcategory)

 **Εξαίρεση**

| Error | Condition |
| --- | --- |
| InvalidOperationException | εάν το όριο ξεπεραστεί |

---

### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |

 **Επιστρέφει:**
void

---

### getGroupingLevelCount {#getGroupingLevelCount}

| Name | Description |
| --- | --- |
| getGroupingLevelCount () | Επιστρέφει τον αριθμό των επιπέδων ομαδοποίησης κατηγοριών που χρησιμοποιούνται. Είναι μεγαλύτερο του ενός για πολυεπίπεδες κατηγορίες. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int

---

### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Επιστρέφει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για το συγχρονισμό της πρόσβασης στη συλλογή. Μόνο για ανάγνωση Object. Επιστρέφει μια ρίζα συγχρονισμού. Μόνο για ανάγνωση Object. |

 **Επιστρέφει:**
Object

---

### getUseCells {#getUseCells}

| Name | Description |
| --- | --- |
| getUseCells () | Εάν true τότε το φύλλο εργασίας χρησιμοποιείται για την αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει πολυεπίπεδες κατηγορίες). Εάν false τότε το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για την αποθήκευση τιμών (και αυτή η περίπτωση δεν υποστηρίζει πολυεπίπεδες κατηγορίες). Ανάγνωση/γγραφή boolean. |

 **Επιστρέφει:**
boolean

---

### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Παίρνει το στοιχείο στον καθορισμένο δείκτη. |

 **Επιστρέφει:**
[ChartCategory](../chartcategory)

 **Εξαίρεση**

| Error | Condition |
| --- | --- |
| ArgumentOutOfRangeException | ο δείκτης δεν είναι έγκυρος δείκτης στο IList. |

---

### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ChartCategory](../chartcategory)) | Αναζητά την καθορισμένη ChartCategory και επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης μέσα σε ολόκληρη τη Συλλογή. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartCategory](../chartcategory) | Κατηγορία διαγράμματος. |

 **Επιστρέφει:**
int

---

### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη Λίστα είναι συγχρονισμένη (ασφαλής για νήματα). Μόνο για ανάγνωση boolean. |

 **Επιστρέφει:**
boolean

---

### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Επιστρέφει έναν ενομετρητή που επαναλαμβάνει τη συλλογο. |

 **Επιστρέφει:**



---

### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

 **Επιστρέφει:**



---

### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([ChartCategory](../chartcategory)) | Αφαιρεί την καθορισμένη τιμή. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartCategory](../chartcategory) | Η τιμή. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Error | Condition |
| --- | --- |
| ArgumentException | Η παράμετρος value δεν βρέθηκε στη συλλογή. |

---

### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Αφαιρεί το στοιχείο στον δεδομένο δείκτη. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης μιας κατηγορίας προς αφαίρεση. |

 **Επιστρέφει:**
void

---

### setUseCells {#setUseCells}

| Name | Description |
| --- | --- |
| setUseCells (boolean) | Εάν true τότε το φύλλο εργασίας χρησιμοποιείται για την αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει πολυεπίπεδες κατηγορίες). Εάν false τότε το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για την αποθήκευση τιμών (και αυτή η περίπτωση δεν υποστηρίζει πολυεπίπεδες κατηγορίες). Ανάγνωση/γγραφή boolean. |

 **Επιστρέφει:**
void

---

### size {#size}

| Name | Description |
| --- | --- |
| size () | Επιστρέφει αριθμό στοιχείων στη συλλογή. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int

---