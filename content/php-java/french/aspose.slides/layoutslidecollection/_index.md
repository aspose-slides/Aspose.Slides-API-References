---
title: LayoutSlideCollection
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/layoutslidecollection/
---
## LayoutSlideCollection classe

 Représente une classe de base pour la collection de diapositives de mise en page.
 
### getByType {#getByType}

| Name | Description |
| --- | --- |
| getByType (byte) | Renvoie la première diapositive de mise en page du type spécifié. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| type | byte | Un type de diapositive de mise en page à rechercher. |

 **Renvoie:**
[LayoutSlide](../layoutslide)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Objet en lecture seule. |

 **Renvoie:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Renvoie la diapositive de mise en page par indice. LayoutSlide en lecture seule. |

 **Renvoie:**
[LayoutSlide](../layoutslide)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Booléen en lecture seule. |

 **Renvoie:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Renvoie:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l'ensemble de la collection. |

 **Renvoie:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([LayoutSlide](../layoutslide)) | Supprime une mise en page de la collection. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| value | [LayoutSlide](../layoutslide) | La diapositive de mise en page à supprimer de la collection. 1) Pour éviter le lancement de PptxEditException, vérifiez d'abord la propriété HasDependingSlides de la mise en page. 2) Vous pouvez également utiliser la méthode ILayoutSlide#remove pour simplifier le code. |

 **Renvoie:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Lancée si la mise en page est utilisée dans la présentation (sa propriété HasDependingSlides est vraie). |


---


### removeUnused {#removeUnused}

| Name | Description |
| --- | --- |
| removeUnused () | Supprime les diapositives de mise en page inutilisées (diapositives de mise en page dont la propriété HasDependingSlides est false). |

 **Renvoie:**
void


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Renvoie le nombre de diapositives de mise en page dans une collection. int en lecture seule. |

 **Renvoie:**
int


---