---
title: ChartSeriesCollection
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente une collection de
type: docs
url: /fr/com.aspose.slides/chartseriescollection/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Représente une collection de [ChartSeries](../../com.aspose.slides/chartseries)
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [size()](#size--) | Renvoie le nombre d'objets dans la collection. |
| [add(int type)](#add-int-) | Crée une nouvelle série de graphique et l'ajoute à la collection. |
| [insert(int index, int type)](#insert-int-int-) | Crée une nouvelle série de graphique et l'insère dans la collection. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Crée une nouvelle série de graphique à partir de [ChartDataCell](../../com.aspose.slides/chartdatacell) et l'ajoute à la collection. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Crée une nouvelle série de graphique à partir de [ChartCellCollection](../../com.aspose.slides/chartcellcollection) et l'ajoute à la collection. |
| [add(String name, int type)](#add-java.lang.String-int-) | Crée une nouvelle série de graphique à partir d'une valeur et l'ajoute à la collection. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Recherche le [ChartSeries](../../com.aspose.slides/chartseries) spécifié et renvoie l'index zéro basé sur la première occurrence dans l'ensemble de la collection. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Supprime la valeur spécifiée. |
| [removeAt(int index)](#removeAt-int-) | Supprime un contrôle ActiveX stocké à la position spécifiée de la collection. |
| [clear()](#clear--) | Supprime tous les contrôles de la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie l'ensemble de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean. |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IChartSeries](../../com.aspose.slides/ichartseries) - L'élément à l'index spécifié.

### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'objets dans la collection. Lecture seule int.

**Retour :**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Crée une nouvelle série de graphique et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Type de série |

**Retour :**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nouvelle série de graphique.

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Crée une nouvelle série de graphique et l'insère dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Retour :**
[IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Crée une nouvelle série de graphique à partir de [ChartDataCell](../../com.aspose.slides/chartdatacell) et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cellule contenant le nom de la série. |
| type | int | Type définissant le type de la série |

--------------------

Si une série de graphique créée à partir de la même cellule existe déjà dans la collection, la méthode n'ajoute rien et renvoie son index. |

**Retour :**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de graphique ajoutée ou série déjà présente dans la collection.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Crée une nouvelle série de graphique à partir de [ChartCellCollection](../../com.aspose.slides/chartcellcollection) et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Cellules contenant le nom de la série. |
| type | int | Type définissant le type de la série |

--------------------

Si une série de graphique créée à partir de la même cellule existe déjà dans la collection, la méthode n'ajoute rien et renvoie son index. |

**Retour :**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de graphique ajoutée ou série déjà présente dans la collection.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Crée une nouvelle série de graphique à partir d'une valeur et l'ajoute à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la série. |
| type | int | Type définissant le type de la série |

**Retour :**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de graphique ajoutée.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Recherche le [ChartSeries](../../com.aspose.slides/chartseries) spécifié et renvoie l'index zéro basé sur la première occurrence dans l'ensemble de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valeur de la série de graphique. |

**Retour :**
int - L'index basé sur zéro de la première occurrence de la valeur dans l'ensemble de la CollectionBase, si trouvé ; sinon, -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Supprime la valeur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | La valeur. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime un contrôle ActiveX stocké à la position spécifiée de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du contrôle à supprimer. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les contrôles de la collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Un java.util.Iterator pour l'ensemble de la collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie l'ensemble de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible |
| index | int | Index dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Retour :**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Retour :**
java.lang.Object