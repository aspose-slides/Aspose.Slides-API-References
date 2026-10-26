---
title: CellCollection
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/cellcollection/
---
## CellCollection κλάση

 Represents a collection of cells.
 
### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει το γονικό presentation μιας CellCollection. Μόνο ανάγνωση IPresentation. |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει το γονικό slide μιας CellCollection. Μόνο ανάγνωση IBaseSlide. |

 **Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Επιστρέφει μια ρίζα συγχρονισμού. Μόνο ανάγνωση Object. |

 **Επιστρέφει:**
Object


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Επιστρέφει ένα κελί με βάση τη θέση του. Μόνο ανάγνωση Cell. Ένα αντικείμενο Cell μπορεί να επιστραφεί για αρκετούς δείκτες σε περίπτωση που το κελί είναι συγχωνευμένο. |

 **Επιστρέφει:**
[Cell](../cell)


---


### isSynchronized {#isSynchronized}

| Όνομα | Περιγραφή |
| --- | --- |
| isSynchronized () | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Επιστρέφει έναν enumerator που επαναλαμβάνει τη συλλογή. |

 **Επιστρέφει:**



---


### iteratorJava {#iteratorJava}

| Όνομα | Περιγραφή |
| --- | --- |
| iteratorJava () | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

 **Επιστρέφει:**



---


### size {#size}

| Όνομα | Περιγραφή |
| --- | --- |
| size () | Επιστρέφει τον αριθμό των κελιών σε μια συλλογή. Μόνο ανάγνωση int. |

 **Επιστρέφει:**
int


---