---
title: ChartSeriesCollection
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/chartseriescollection/
---
## ChartSeriesCollection κλάση

 Ανεπαριστά τη συλλογή των   ChartSeries

### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (int) | Δημιουργεί νέα ChartSeries και την προσθέτει στη συλλογή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Τύπος της σειράς |

 **Επιστρέφει:**
[ChartSeries](../chartseries)


---


### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add ([ChartDataCell](../chartdatacell), int) | Δημιουργεί νέα ChartSeries από ChartDataCell και την προσθέτει στη συλλογή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| cellWithSeriesName | [ChartDataCell](../chartdatacell) | Cell που περιέχει το όνομα της σειράς. |
| type | int | Τύπος που ορίζει τον τύπο της σειράς. Αν η ChartSeries δημιουργηθεί από ίδιο κελί που υπάρχει ήδη στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το ευρετήριο της. |

 **Επιστρέφει:**
[ChartSeries](../chartseries)


---


### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add ([ChartCellCollection](../chartcellcollection), int) | Δημιουργεί νέα ChartSeries από ChartCellCollection και την προσθέτει στη συλλογή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| cellsWithSeriesName | [ChartCellCollection](../chartcellcollection) | Cells που περιέχουν το όνομα της σειράς. |
| type | int | Τύπος που ορίζει τον τύπο της σειράς. Αν η ChartSeries δημιουργηθεί από ίδιο κελί που υπάρχει ήδη στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το ευρετήριο της. |

 **Επιστρέφει:**
[ChartSeries](../chartseries)


---


### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (String, int) | Δημιουργεί νέα ChartSeries από τιμή και την προσθέτει στη συλλογή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα σειράς. |
| type | int | Τύπος που ορίζει τον τύπο της σειράς. |

 **Επιστρέφει:**
[ChartSeries](../chartseries)


---


### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Καταργεί όλα τα controls από τη συλλογή. |

 **Επιστρέφει:**
void


---


### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Επιστρέφει ένα ριζικό αντικείμενο συγχρονισμού. Μόνο για ανάγνωση Object. |

 **Επιστρέφει:**
Object


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Λαμβάνει το στοιχείο στο καθορισμένο ευρετήριο. |

 **Επιστρέφει:**
[ChartSeries](../chartseries)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | Το ευρετήριο δεν είναι έγκυρο ευρετήριο στη IList. |


---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([ChartSeries](../chartseries)) | Αναζητά το καθορισμένο ChartSeries και επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης εντός ολόκληρης της Συλλογής |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | Τιμή σειράς ChartSeries. |

 **Επιστρέφει:**
int


---


### insert {#insert}

| Όνομα | Περιγραφή |
| --- | --- |
| insert (int, int) | Δημιουργεί νέα ChartSeries και την εισάγει στη συλλογή. |

 **Επιστρέφει:**
[ChartSeries](../chartseries)


---


### isSynchronized {#isSynchronized}

| Όνομα | Περιγραφή |
| --- | --- |
| isSynchronized () | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |

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
| remove ([ChartSeries](../chartseries)) | Αφαιρεί την καθορισμένη τιμή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | Η τιμή. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Η παράμετρος value δεν βρέθηκε στη συλλογή. |


---


### removeAt {#removeAt}

| Όνομα | Περιγραφή |
| --- | --- |
| removeAt (int) | Αφαιρεί έναν έλεγχο ActiveX που βρίσκεται στη καθορισμένη θέση από τη συλλογή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του ελέγχου προς αφαίρεση. |

 **Επιστρέφει:**
void


---


### size {#size}

| Όνομα | Περιγραφή |
| --- | --- |
| size () | Επιστρέφει τον αριθμό των αντικειμένων στη συλλογή. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int


---