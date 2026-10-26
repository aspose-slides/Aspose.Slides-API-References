---
title: LayoutSlideCollection
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/layoutslidecollection/
---
## LayoutSlideCollection κλάση

Αντιπροσωπεύει μια βασική κλάση για τη συλλογή των διαφανειών διάταξης.
 
### getByType {#getByType}

| Όνομα | Περιγραφή |
| --- | --- |
| getByType (byte) | Επιστρέφει την πρώτη διαφάνεια διάταξης του καθορισμένου τύπου. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | byte | Τύπος διαφάνειας διάταξης προς εύρεση. |

**Επιστρέφει:**
[LayoutSlide](../layoutslide)


---


### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Επιστρέφει μια ρίζα συγχρονισμού. Μόνο-ανάγνωση Object. |

**Επιστρέφει:**
Object


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Επιστρέφει τη διαφάνεια διάταξης με βάση τον δείκτη. Μόνο-ανάγνωση LayoutSlide. |

**Επιστρέφει:**
[LayoutSlide](../layoutslide)


---


### isSynchronized {#isSynchronized}

| Όνομα | Περιγραφή |
| --- | --- |
| isSynchronized () | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο-ανάγνωση boolean. |

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
| remove ([LayoutSlide](../layoutslide)) | Αφαιρεί μια διάταξη από τη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [LayoutSlide](../layoutslide) | Η διαφάνεια διάταξης που θα αφαιρεθεί από τη συλλογή. 1) Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides της διάταξης πριν. 2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο ILayoutSlide#remove για να απλοποιήσετε τον κώδικα. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxEditException | Εκβάλλεται εάν η διάταξη χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides είναι true). |


---


### removeUnused {#removeUnused}

| Όνομα | Περιγραφή |
| --- | --- |
| removeUnused () | Αφαιρεί τις αχρησιμοποίητες διαφάνειες διάταξης (διαφάνειες διάταξης των οποίων η ιδιότητα HasDependingSlides είναι false). |

**Επιστρέφει:**
void


---


### size {#size}

| Όνομα | Περιγραφή |
| --- | --- |
| size () | Επιστρέφει τον αριθμό των διαφανειών διάταξης σε μια συλλογή. Μόνο-ανάγνωση int. |

**Επιστρέφει:**
int


---