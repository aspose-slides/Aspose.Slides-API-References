---
title: SectionCollection
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/sectioncollection/
---
## SectionCollection classe

 Représente une collection de sections.
 
### addEmptySection {#addEmptySection}

| Nom | Description |
| --- | --- |
| addEmptySection (String, int) | Ajoute une section vide à la position spécifiée de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la section |
| index | int | Indice de la nouvelle section. |

 **Valeur retournée :**
[Section](../section)


---


### addSection {#addSection}

| Nom | Description |
| --- | --- |
| addSection (String, [Slide](../slide)) | Ajoute une section de diapositives démarrée à partir d'une diapositive spécifique. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la section |
| startedFromSlide | [Slide](../slide) | Première diapositive de la section |

 **Valeur retournée :**
[Section](../section)


---


### appendEmptySection {#appendEmptySection}

| Nom | Description |
| --- | --- |
| appendEmptySection (String) | Ajoute une section vide à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la section |

 **Valeur retournée :**
[Section](../section)


---


### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime toutes les sections de la collection. |

 **Valeur retournée :**
void


---


### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Retourne une racine de synchronisation. Lecture seule Object. |

 **Valeur retournée :**
Object


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l'élément à l'indice spécifié. Lecture seule ISection. |

 **Valeur retournée :**
[Section](../section)


---


### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([Section](../section)) | Retourne l'indice de la section spécifiée dans la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | Section à trouver. |

 **Valeur retournée :**
int


---


### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Retourne une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean. |

 **Valeur retournée :**
boolean


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Retourne un énumérateur qui parcourt la collection. |

 **Valeur retournée :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Retourne un itérateur java pour l'intégralité de la collection. |

 **Valeur retournée :**



---


### removeSection {#removeSection}

| Nom | Description |
| --- | --- |
| removeSection ([Section](../section)) | Supprime la section. Les diapositives contenues dans la section seront fusionnées dans la section précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | La section à supprimer de la collection. |

 **Valeur retournée :**
void


---


### removeSectionWithSlides {#removeSectionWithSlides}

| Nom | Description |
| --- | --- |
| removeSectionWithSlides ([Section](../section)) | Supprime la section et les diapositives qu'elle contient. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | La section à supprimer de la collection. |

 **Valeur retournée :**
void


---


### reorderSectionWithSlides {#reorderSectionWithSlides}

| Nom | Description |
| --- | --- |
| reorderSectionWithSlides ([Section](../section), int) | Déplace la section et ses diapositives de la collection vers la position spécifiée. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | [Section](../section) | Indice cible. |
| section | int | Section à déplacer. |

 **Valeur retournée :**
void


---


### size {#size}

| Nom | Description |
| --- | --- |
| size () | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int. |

 **Valeur retournée :**
int


---