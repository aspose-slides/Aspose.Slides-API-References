---
title: PieSplitCustomPointCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/piesplitcustompointcollection/
---
## PieSplitCustomPointCollection classe

 Représente une collection de points pour le point de division dans un graphique anneau-sur-anneau ou un graphique anneau-dans-anneau avec une division personnalisée.
 
### add {#add}

| Nom | Description |
| --- | --- |
| add (int) | Ajoute le point de données par son indice dans la collection de points de la série parente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Indice du point de données dans la collection de points de la série parente. |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Le point avec l'indice donné n'a pas été trouvé. |


---


### addItem {#addItem}

| Nom | Description |
| --- | --- |
| addItem ([ChartDataPoint](../chartdatapoint)) | Ajoute un point de données à la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| dataPoint | [ChartDataPoint](../chartdatapoint) | Point de données à ajouter. |

 **Retour :**
void


---


### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les éléments de l'IGenericCollection. |

 **Retour :**
void


---


### containsItem {#containsItem}

| Nom | Description |
| --- | --- |
| containsItem ([ChartDataPoint](../chartdatapoint)) | Détermine si l'IGenericCollection contient une valeur spécifique. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| item | [ChartDataPoint](../chartdatapoint) | L'objet à rechercher dans l'IGenericCollection. |

 **Retour :**
boolean


---


### copyToTArray {#copyToTArray}

| Nom | Description |
| --- | --- |
| copyToTArray (com.aspose.slides.IChartDataPoint[], int) | Copie les éléments de l'IGenericCollection dans un tableau, en commençant à un indice de tableau particulier. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IChartDataPoint[] | Le tableau unidimensionnel qui est la destination des éléments copiés depuis IGenericCollection. Le tableau doit être indexé à partir de zéro. |
| arrayIndex | int | L'indice de départ basé sur zéro dans le tableau où commence la copie. |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Le nombre d'éléments dans l'IGenericCollection source est supérieur à l'espace disponible depuis arrayIndex jusqu'à la fin du tableau de destination. |


---


### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Objet en lecture seule. |

 **Retour :**
Object


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Renvoie le point de données du diagramme pour l'index spécifié. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice. |

 **Retour :**
[ChartDataPoint](../chartdatapoint)


---


### isReadOnly {#isReadOnly}

| Nom | Description |
| --- | --- |
| isReadOnly () | Obtient une valeur indiquant si l'IGenericCollection est en lecture seule. Lecture seule boolean. |

 **Retour :**
boolean


---


### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean. |

 **Retour :**
boolean


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Retour :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l'ensemble de la collection. |

 **Retour :**



---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove (int) | Supprime l'élément de la collection par son indice dans la collection de points de la série parente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Indice du point de données dans la collection de points de la série parente. |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | dataPointIndex est négatif. |


---


### removeItem {#removeItem}

| Nom | Description |
| --- | --- |
| removeItem ([ChartDataPoint](../chartdatapoint)) | Supprime l'élément de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| dataPoint | [ChartDataPoint](../chartdatapoint) | Point de données à supprimer. |

 **Retour :**
boolean


---


### size {#size}

| Nom | Description |
| --- | --- |
| size () | Renvoie ou définit le nombre de points de données du diagramme. Lecture seule int. |

 **Retour :**
int


---