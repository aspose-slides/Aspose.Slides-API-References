---
title: CommentAuthorCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/commentauthorcollection/
---
## CommentAuthorCollection classe

 Représente une collection d'auteurs de commentaires.
 
### addAuthor {#addAuthor}

| Nom | Description |
| --- | --- |
| addAuthor (String, String) | Ajoute un nouvel auteur à la fin d'une collection. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom d'un nouvel auteur. |
| initials | String | Initiales d'un nouvel auteur. |

 **Retour:**
[CommentAuthor](../commentauthor)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | PptxEditException | Levée si un auteur avec le même nom et les mêmes initiales est déjà ajouté. |


---


### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les auteurs d'une collection. |

 **Retour:**
void


---


### findByName {#findByName}

| Nom | Description |
| --- | --- |
| findByName (String) | Recherche un auteur dans une collection par son nom. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom d'un auteur à rechercher. |

 **Retour:**
[CommentAuthor](../commentauthor)


---


### findByNameAndInitials {#findByNameAndInitials}

| Nom | Description |
| --- | --- |
| findByNameAndInitials (String, String) | Recherche un auteur dans une collection par son nom et ses initiales. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom d'un auteur à rechercher. |
| initials | String | Initiales d'un auteur à rechercher. |

 **Retour:**
[CommentAuthor](../commentauthor)


---


### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Objet en lecture seule. |

 **Retour:**
Object


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l'élément à l'index spécifié. ICommentAuthor en lecture seule. |

 **Retour:**
[CommentAuthor](../commentauthor)


---


### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (sans danger pour les threads). booléen en lecture seule. |

 **Retour:**
boolean


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Retour:**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l'ensemble de la collection. |

 **Retour:**



---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([CommentAuthor](../commentauthor)) | Supprime la première occurrence de l'auteur spécifié dans une collection. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| author | [CommentAuthor](../commentauthor) | L'auteur à supprimer d'une collection. |

 **Retour:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | PptxEditException | Levée si l'auteur est déjà supprimé. |


---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime l'auteur à l'index spécifié de la collection. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé à zéro de l'élément à supprimer. |

 **Retour:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | PptxEditException | Levée si l'auteur est déjà supprimé. |


---


### size {#size}

| Nom | Description |
| --- | --- |
| size () | Obtient le nombre d'éléments réellement contenus dans la collection. int en lecture seule. |

 **Retour:**
int


---


### toArray {#toArray}

| Nom | Description |
| --- | --- |
| toArray () | Crée et renvoie un tableau contenant tous les auteurs. |

 **Retour:**
[CommentAuthor](../commentauthor)


---