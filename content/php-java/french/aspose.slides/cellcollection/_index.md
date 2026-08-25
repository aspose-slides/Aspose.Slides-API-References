---
title: CellCollection
second_title: Référence de l'API Java via Aspose.Slides pour PHP
description: 
type: docs
url: /fr/aspose.slides/cellcollection/
---
## CellCollection classe

Représente une collection de cellules.
 
### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parente d'une CellCollection. Lecture seule IPresentation. |

**Renvoie :**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parente d'une CellCollection. Lecture seule IBaseSlide. |

**Renvoie :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Lecture seule Object. |

**Renvoie :**
Object


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Renvoie une cellule par sa position. Lecture seule Cell. Un objet Cell peut être renvoyé pour plusieurs indices si la cellule est fusionnée. |

**Renvoie :**
[Cell](../cell)


---


### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean. |

**Renvoie :**
boolean


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

**Renvoie :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l'ensemble de la collection. |

**Renvoie :**



---


### size {#size}

| Nom | Description |
| --- | --- |
| size () | Renvoie le nombre de cellules dans une collection. Lecture seule int. |

**Renvoie :**
int


---