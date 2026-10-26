---
title: MotionPath
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/motionpath/
---
## MotionPath κλάση

Αντιπροσωπεύει το μονοπάτι κίνησης.

### MotionPath {#MotionPath}

| Όνομα | Περιγραφή |
| --- | --- |
| MotionPath() |  |

**Επιστρέφει:**
MotionPath


---


### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (int, java.awt.geom.Point2D.Float[], int, boolean) | Προσθέτει νέα εντολή στο μονοπάτι |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | MotionCommandPathType |
| pts | java.awt.geom.Point2D.Float[] | Πίνακας σημείων |
| ptsType | int | MotionPathPointsType |
| bRelativeCoord | boolean | Boolean σχετικών συντεταγμένων |

**Επιστρέφει:**
[MotionCmdPath](../motioncmdpath)


---


### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Αφαιρεί όλες τις εντολές από τη συλλογή. |

**Επιστρέφει:**
void


---


### getCount {#getCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getCount () | Επιστρέφει τον αριθμό των μονοπατιών στη συλλογή. Μόνο ανάγνωση int. |

**Επιστρέφει:**
int


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Επιστρέφει μια εντολή στο συγκεκριμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**
[MotionCmdPath](../motioncmdpath)


---


### insert {#insert}

| Όνομα | Περιγραφή |
| --- | --- |
| insert (int, int, java.awt.geom.Point2D.Float[], int, boolean) | Εισάγει νέα εντολή στο μονοπάτι |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο πρέπει να εισαχθεί το στοιχείο. |
| type | int | MotionCommandPathType |
| pts | java.awt.geom.Point2D.Float[] | Πίνακας σημείων |
| ptsType | int | MotionPathPointsType |
| bRelativeCoord | boolean | Boolean σχετικών συντεταγμένων |

**Επιστρέφει:**
void


---


### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή. |

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
| remove ([MotionCmdPath](../motioncmdpath)) | Αφαιρεί τις καθορισμένες εντολές από τη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [MotionCmdPath](../motioncmdpath) | Μονοπάτι κίνησης προς αφαίρεση. |

**Επιστρέφει:**
void


---


### removeAt {#removeAt}

| Όνομα | Περιγραφή |
| --- | --- |
| removeAt (int) | Αφαιρεί μια εντολή στο συγκεκριμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας εντολής που πρέπει να διαγραφεί. |

**Επιστρέφει:**
void


---