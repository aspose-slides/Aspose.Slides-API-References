---
title: MasterSlideCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/masterslidecollection/
---
## MasterSlideCollection classe

Représente une collection de diapositives maîtres.

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([MasterSlide](../masterslide)) | Ajoute une copie d'une diapositive maîtresse spécifiée à la fin de la collection. Les diapositives de mise en page liées seront également copiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceMaster | [MasterSlide](../masterslide) | Diapositive à cloner. |

**Renvoie :**
[MasterSlide](../masterslide)

---


### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Retourne une racine de synchronisation. Objet en lecture seule. |

**Renvoie :**
Object

---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l'élément à l'index spécifié. MasterSlide en lecture seule. |

**Renvoie :**
[MasterSlide](../masterslide)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [MasterSlide](../masterslide)) | Insère une copie d'une diapositive maîtresse spécifiée à la position indiquée de la collection. Les diapositives de mise en page liées seront également copiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| sourceMaster | [MasterSlide](../masterslide) | Diapositive à cloner. |

**Renvoie :**
[MasterSlide](../masterslide)

---


### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Retourne une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). booléen en lecture seule. |

**Renvoie :**
boolean

---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Retourne un énumérateur qui parcourt la collection. |

**Renvoie :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Retourne un itérateur java pour l'ensemble de la collection. |

**Renvoie :**



---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([MasterSlide](../masterslide)) | Supprime la première occurrence d'un objet spécifique de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| value | [MasterSlide](../masterslide) | La diapositive maîtresse à supprimer de la collection. |

**Renvoie :**
void

---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime l'élément à l'index spécifié de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. Pour éviter le lancement de PptxEditException, vérifiez au préalable la propriété HasDependingSlides du maître. |

**Renvoie :**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Lancée si le maître à supprimer est utilisé dans la présentation (sa propriété HasDependingSlides est vraie). |

---


### removeUnused {#removeUnused}

| Nom | Description |
| --- | --- |
| removeUnused (boolean) | Supprime les maîtres non utilisés. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | Détermine si cette méthode doit supprimer les maîtres inutilisés même si leur propriété MasterSlide#getPreserve / MasterSlide#setPreserve(boolean) est définie sur true. |

**Renvoie :**
void

---


### size {#size}

| Nom | Description |
| --- | --- |
| size () | Obtient le nombre d'éléments réellement contenus dans la collection. int en lecture seule. |

**Renvoie :**
int

---