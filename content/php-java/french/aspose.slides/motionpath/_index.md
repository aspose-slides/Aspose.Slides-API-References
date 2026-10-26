---
title: MotionPath
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/motionpath/
---
## MotionPath classe

Représente un chemin de mouvement.

### MotionPath {#MotionPath}

| Nom | Description |
| --- | --- |
| MotionPath() |  |

**Renvoie:**  
MotionPath


---


### add {#add}

| Nom | Description |
| --- | --- |
| add (int, java.awt.geom.Point2D.Float[], int, boolean) | Ajoute une nouvelle commande au chemin |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| type | int | MotionCommandPathType |
| pts | java.awt.geom.Point2D.Float[] | Tableau de points |
| ptsType | int | MotionPathPointsType |
| bRelativeCoord | boolean | Booléen de coordonnées relatives |

**Renvoie:**  
[MotionCmdPath](../motioncmdpath)


---


### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime toutes les commandes de la collection. |

**Renvoie:**  
void


---


### getCount {#getCount}

| Nom | Description |
| --- | --- |
| getCount () | Renvoie le nombre de chemins dans la collection. int en lecture seule. |

**Renvoie:**  
int


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Renvoie une commande à l'index spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Renvoie:**  
[MotionCmdPath](../motioncmdpath)


---


### insert {#insert}

| Nom | Description |
| --- | --- |
| insert (int, int, java.awt.geom.Point2D.Float[], int, boolean) | Insère une nouvelle commande au chemin |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à laquelle l'élément doit être inséré. |
| type | int | MotionCommandPathType |
| pts | java.awt.geom.Point2D.Float[] | Tableau de points |
| ptsType | int | MotionPathPointsType |
| bRelativeCoord | boolean | Booléen de coordonnées relatives |

**Renvoie:**  
void


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

**Renvoie:**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l'ensemble de la collection. |

**Renvoie:**



---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([MotionCmdPath](../motioncmdpath)) | Supprime les commandes spécifiées de la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| item | [MotionCmdPath](../motioncmdpath) | Chemin de mouvement à supprimer. |

**Renvoie:**  
void


---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime une commande à l'index spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index d'une commande qui doit être supprimée. |

**Renvoie:**  
void


---