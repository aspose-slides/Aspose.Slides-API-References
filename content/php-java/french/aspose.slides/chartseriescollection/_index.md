---
title: ChartSeriesCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/chartseriescollection/
---
## ChartSeriesCollection classe

 Représente une collection de   ChartSeries

### add {#add}

| Nom | Description |
| --- | --- |
| add (int) | Crée une nouvelle série de graphique et l’ajoute à la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| type | int | Type de série |

 **Valeur de retour :**
[ChartSeries](../chartseries)

---

### add {#add}

| Nom | Description |
| --- | --- |
| add ([ChartDataCell](../chartdatacell), int) | Crée une nouvelle série de graphique à partir de ChartDataCell et l’ajoute à la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [ChartDataCell](../chartdatacell) | Cellule contenant le nom de la série. |
| type | int | Type définissant le type de la série. Si une série de graphique créée à partir de la même cellule existe déjà dans la collection, la méthode n’ajoute rien et renvoie son indice. |

 **Valeur de retour :**
[ChartSeries](../chartseries)

---

### add {#add}

| Nom | Description |
| --- | --- |
| add ([ChartCellCollection](../chartcellcollection), int) | Crée une nouvelle série de graphique à partir de ChartCellCollection et l’ajoute à la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [ChartCellCollection](../chartcellcollection) | Cellules contenant le nom de la série. |
| type | int | Type définissant le type de la série. Si une série de graphique créée à partir de la même cellule existe déjà dans la collection, la méthode n’ajoute rien et renvoie son indice. |

 **Valeur de retour :**
[ChartSeries](../chartseries)

---

### add {#add}

| Nom | Description |
| --- | --- |
| add (String, int) | Crée une nouvelle série de graphique à partir de la valeur et l’ajoute à la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la série. |
| type | int | Type définissant le type de la série |

 **Valeur de retour :**
[ChartSeries](../chartseries)

---

### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les contrôles de la collection. |

 **Valeur de retour :**
void

---

### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Objet en lecture seule. |

 **Valeur de retour :**
Object

---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Récupère l’élément à l’indice spécifié. |

 **Valeur de retour :**
[ChartSeries](../chartseries)

 **Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentOutOfRangeException | l’index n’est pas un index valide dans l’IList. |

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([ChartSeries](../chartseries)) | Recherche la ChartSeries spécifiée et renvoie l’indice basé sur zéro de la première occurrence dans toute la collection |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | Valeur de la série de graphique. |

 **Valeur de retour :**
int

---

### insert {#insert}

| Nom | Description |
| --- | --- |
| insert (int, int) | Crée une nouvelle série de graphique et l’insère dans la collection. |

 **Valeur de retour :**
[ChartSeries](../chartseries)

---

### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). Booléen en lecture seule. |

 **Valeur de retour :**
boolean

---

### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un itérateur qui parcourt la collection. |

 **Valeur de retour :**



---

### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour la collection entière. |

 **Valeur de retour :**



---

### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([ChartSeries](../chartseries)) | Supprime la valeur spécifiée. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | La valeur. |

 **Valeur de retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Le paramètre value n’a pas été trouvé dans la collection. |

---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime un contrôle ActiveX stocké à la position spécifiée de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice du contrôle à supprimer. |

 **Valeur de retour :**
void

---

### size {#size}

| Nom | Description |
| --- | --- |
| size () | Renvoie le nombre d’objets dans la collection. Int en lecture seule. |

 **Valeur de retour :**
int

---