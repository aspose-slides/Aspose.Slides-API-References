---
title: PieSplitCustomPointCollection
second_title: Aspose.Sildes για PHP μέσω Java API
description: 
type: docs
url: /el/aspose.slides/piesplitcustompointcollection/
---
## PieSplitCustomPointCollection κλάση

Αντιπροσωπεύει μια συλλογή σημείων για το σημείο διαίρεσης σε γραφήματα bar-of-pie ή pie-of-pie με προσαρμοσμένη διαίρεση.

### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (int) | Adds data point by its index in parent series points collection. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentException | Point with the given index was not found". |

---

### addItem {#addItem}

| Όνομα | Περιγραφή |
| --- | --- |
| addItem ([ChartDataPoint](../chartdatapoint)) | Προσθέτει σημείο δεδομένων στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPoint | [ChartDataPoint](../chartdatapoint) | Data point add to. |

**Επιστρέφει:**
void

---

### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Αφαιρεί όλα τα στοιχεία από το IGenericCollection. |

**Επιστρέφει:**
void

---

### containsItem {#containsItem}

| Όνομα | Περιγραφή |
| --- | --- |
| containsItem ([ChartDataPoint](../chartdatapoint)) | Καθορίζει εάν το IGenericCollection περιέχει μια συγκεκριμένη τιμή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ChartDataPoint](../chartdatapoint) | Το αντικείμενο που εντοπίζεται στο IGenericCollection. |

**Επιστρέφει:**
boolean

---

### copyToTArray {#copyToTArray}

| Όνομα | Περιγραφή |
| --- | --- |
| copyToTArray (com.aspose.slides.IChartDataPoint[], int) | Αντιγράφει τα στοιχεία του IGenericCollection σε έναν Array, ξεκινώντας από έναν συγκεκριμένο δείκτη Array. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.slides.IChartDataPoint[] | Ο μονοδιάστατος Array που είναι ο προορισμός των στοιχείων που αντιγράφονται από το IGenericCollection. Ο Array πρέπει να έχει μηδενική αρίθμηση. |
| arrayIndex | int | Ο μηδενικός δείκτης στον array από τον οποίο αρχίζει η αντιγραφή. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Ο αριθμός των στοιχείων στην πηγή IGenericCollection είναι μεγαλύτερος από το διαθέσιμο χώρο από το arrayIndex μέχρι το τέλος του προορισμού array. |

---

### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Επιστρέφει μια ρίζα συγχρονισμού. Object μόνο για ανάγνωση. |

**Επιστρέφει:**
Object

---

### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Επιστρέφει το σημείο δεδομένων του διαγράμματος για το συγκεκριμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης. |

**Επιστρέφει:**
[ChartDataPoint](../chartdatapoint)

---

### isReadOnly {#isReadOnly}

| Όνομα | Περιγραφή |
| --- | --- |
| isReadOnly () | Λαμβάνει μια τιμή που υποδεικνύει εάν το IGenericCollection είναι μόνο για ανάγνωση. Boolean μόνο για ανάγνωση. |

**Επιστρέφει:**
boolean

---

### isSynchronized {#isSynchronized}

| Όνομα | Περιγραφή |
| --- | --- |
| isSynchronized () | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Boolean μόνο για ανάγνωση. |

**Επιστρέφει:**
boolean

---

### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή. |

**Επιστρέφει:**



---

### iteratorJava {#iteratorJava}

| Όνομα | Περιγραφή |
| --- | --- |
| iteratorJava () | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

**Επιστρέφει:**



---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove (int) | Αφαιρεί στοιχείο από τη συλλογή με το δείκτη του στη συλλογή σημείων της γονικής σειράς. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | Το dataPointIndex είναι αρνητικό. |

---

### removeItem {#removeItem}

| Όνομα | Περιγραφή |
| --- | --- |
| removeItem ([ChartDataPoint](../chartdatapoint)) | Αφαιρεί στοιχείο από τη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPoint | [ChartDataPoint](../chartdatapoint) | Data point remove to. |

**Επιστρέφει:**
boolean

---

### size {#size}

| Όνομα | Περιγραφή |
| --- | --- |
| size () | Επιστρέφει ή ορίζει τον αριθμό των σημείων δεδομένων του διαγράμματος. int μόνο για ανάγνωση. |

**Επιστρέφει:**
int