---
title: SmartArtNodeCollection
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/smartartnodecollection/
---
## SmartArtNodeCollection κλάση

 Αντιπροσωπεύει μια συλλογή από κόμβους SmartArt.
 
### addNode {#addNode}

| Όνομα | Περιγραφή |
| --- | --- |
| addNode () | Προσθέτει νέο κόμβο SmartArt ή υποκόμβο. |

 **Επιστρέφει:**
[SmartArtNode](../smartartnode)


---


### addNodeByPosition {#addNodeByPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| addNodeByPosition (int) | Προσθέτει νέο κόμβο στη επιλεγμένη θέση της συλλογής κόμβων |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | int | Θέση κόμβου με βάση το μηδέν |

 **Επιστρέφει:**
[SmartArtNode](../smartartnode)

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentOutOfRangeException | position is less than 0 |


---


### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Επιστρέφει μια ρίζα συγχρονισμού. Αντικείμενο μόνο για ανάγνωση. |

 **Επιστρέφει:**
Object


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Επιστρέφει κόμβο με βάση τον δείκτη |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης του στοιχείου με βάση το μηδέν |

 **Επιστρέφει:**
[SmartArtNode](../smartartnode)


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


### removeNode {#removeNode}

| Όνομα | Περιγραφή |
| --- | --- |
| removeNode (int) | Αφαιρεί κόμβο ή υποκόμβο με βάση τον δείκτη |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης κόμβου με βάση το μηδέν |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentOutOfRangeException | index is less than 0. -or- index is equal to or greater than siblings count |


---


### removeNode {#removeNode}

| Όνομα | Περιγραφή |
| --- | --- |
| removeNode ([SmartArtNode](../smartartnode)) | Αφαιρεί κόμβο ή υποκόμβο |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [SmartArtNode](../smartartnode) | Κόμβος προς αφαίρεση |

 **Επιστρέφει:**
void


---


### size {#size}

| Όνομα | Περιγραφή |
| --- | --- |
| size () | Επιστρέφει τον αριθμό των κόμβων στη συλλογή. int μόνο για ανάγνωση. |

 **Επιστρέφει:**
int


---