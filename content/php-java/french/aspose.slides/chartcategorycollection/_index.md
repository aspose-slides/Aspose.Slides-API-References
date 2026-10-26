---
title: ChartCategoryCollection
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs
url: /fr/aspose.slides/chartcategorycollection/
---
## ChartCategoryCollection classe

 Représente une collection de ChartCategory

### add {#add}

| Nom | Description |
| --- | --- |
| add ([ChartDataCell](../chartdatacell)) | Si la catégorie existe dans la collection, la retourne. Sinon crée une nouvelle ChartCategory à partir de IChartDataCell et l'ajoute à la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| chartDataCell | [ChartDataCell](../chartdatacell) | Cell utilisée pour créer la ChartCategory. |

**Renvoie:**
[ChartCategory](../chartcategory)

---

### add {#add}

| Nom | Description |
| --- | --- |
| add (Object) | Crée une nouvelle ChartCategory à partir de la valeur et l'ajoute à la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | Object | La valeur. Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez ChartDataWorkbook pour ajouter ou modifier des valeurs de cellules, assurez-vous de ne pas utiliser cette feuille de calcul. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680 |

**Renvoie:**
[ChartCategory](../chartcategory)

**Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | si la limite est dépassée |

---

### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les éléments de la collection. |

**Renvoie:**
void

---

### getGroupingLevelCount {#getGroupingLevelCount}

| Nom | Description |
| --- | --- |
| getGroupingLevelCount () | Renvoie le nombre de niveaux de groupement de catégories utilisés. Est supérieur à un pour les catégories à plusieurs niveaux. Lecture seule int. |

**Renvoie:**
int

---

### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Renvoie un objet pouvant être utilisé pour synchroniser l'accès à la collection. Lecture seule Object. Renvoie une racine de synchronisation. Lecture seule Object. |

**Renvoie:**
Object

---

### getUseCells {#getUseCells}

| Nom | Description |
| --- | --- |
| getUseCells () | Si true alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). Si false alors la feuille de calcul n'est PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Lecture/écriture boolean. |

**Renvoie:**
boolean

---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l'élément à l'index spécifié. |

**Renvoie:**
[ChartCategory](../chartcategory)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | l'index n'est pas un index valide dans IList. |

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([ChartCategory](../chartcategory)) | Recherche la ChartCategory spécifiée et renvoie l'index basé sur zéro de la première occurrence dans l'ensemble de la Collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | [ChartCategory](../chartcategory) | Catégorie de graphique. |

**Renvoie:**
int

---

### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la List est synchronisé (thread safe). Lecture seule boolean. |

**Renvoie:**
boolean

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
| remove ([ChartCategory](../chartcategory)) | Supprime la valeur spécifiée. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | [ChartCategory](../chartcategory) | La valeur. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Le paramètre value n'a pas été trouvé dans la collection. |

---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime l'élément à l'index donné. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index d'une catégorie à supprimer. |

**Renvoie:**
void

---

### setUseCells {#setUseCells}

| Nom | Description |
| --- | --- |
| setUseCells (boolean) | Si true alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux). Si false alors la feuille de calcul n'est PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Lecture/écriture boolean. |

**Renvoie:**
void

---

### size {#size}

| Nom | Description |
| --- | --- |
| size () | Renvoie le nombre d'éléments dans la collection. Lecture seule int. |

**Renvoie:**
int

---