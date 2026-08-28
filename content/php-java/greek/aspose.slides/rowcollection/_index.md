---
title: RowCollection
second_title: Aspose.Sildes για PHP μέσω Java API Reference
description: 
type: docs

url: /el/aspose.slides/rowcollection/
---
## RowCollection κλάση

Αντιπροσωπεύει τη συλλογή γραμμών πίνακα.

### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Row](../row), boolean) | Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| templ | [Row](../row) | Γραμμή που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | Αληθές για αντιγραφή επίσης όλων των γραμμών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

**Τιμή επιστροφής:**
[Row](../row)

---

### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Επιστρέφει μια ρίζα συγχορωνισμού. Μόνο για ανάγνωση Object. |

**Τιμή επιστροφής:**
Object

---

### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Επιστρέφει τη γραμμή στον καθορισμένο δείκτη. Μόνο για ανάγνωση Row. |

**Τιμή επιστροφής:**
[Row](../row)

---

### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Row](../row), boolean) | Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στη καθορισμένη θέση σε έναν πίνακα. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης μιας νέας γραμμής. |
| templ | [Row](../row) | Γραμμή που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | Αληθές για αντιγραφή επίσης όλων των γραμμών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

**Τιμή επιστροφής:**
[Row](../row)

---

### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean. |

**Τιμή επιστροφής:**
boolean

---

### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |

**Τιμή επιστροφής:**



---

### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

**Τιμή επιστροφής:**



---

### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int, boolean) | Καταργεί μια γραμμή στην καθορισμένη θέση από έναν πίνακα. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Δείκτης μιας γραμμής προς διαγραφή. |
| withAttachedRows | boolean | Αληθές για διαγραφή επίσης όλων των συνδεδεμένων γραμμών. |

**Τιμή επιστροφής:**
void

---

### size {#size}

| Name | Description |
| --- | --- |
| size () | Λαμβάνει τον αριθμό των γραμμών που περιέχονται στην συλλογή. Μόνο για ανάγνωση int. |

**Τιμή επιστροφής:**
int

---