---
title: IChartSeriesCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente la collection de
type: docs
url: /fr/com.aspose.slides/ichartseriescollection/
---
**Toutes les interfaces implémentées:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Représente la collection de [IChartSeries](../../com.aspose.slides/ichartseries)
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [add(int type)](#add-int-) | Crée une nouvelle série de graphique et l'ajoute à la collection. |
| [insert(int index, int type)](#insert-int-int-) | Crée une nouvelle série de graphique et l'insère dans la collection. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Crée une nouvelle série de graphique à partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) et l'ajoute à la collection. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Crée une nouvelle série de graphique à partir de [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) et l'ajoute à la collection. |
| [add(String name, int type)](#add-java.lang.String-int-) | Crée une nouvelle série de graphique à partir d'une valeur et l'ajoute à la collection. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Recherche le [IChartSeries](../../com.aspose.slides/ichartseries) spécifié et renvoie l'index de base zéro de la première occurrence dans l'ensemble de la collection. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Supprime la valeur spécifiée. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié |
| [clear()](#clear--) | Supprime tous les éléments (y compris le style du graphique) de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Obtient l'élément à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[IChartSeries](../../com.aspose.slides/ichartseries) - L'élément à l'index spécifié.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Crée une nouvelle série de graphique et l'ajoute à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Type de série |

**Renvoie:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nouvelle série de graphique.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Crée une nouvelle série de graphique et l'insère dans la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'insertion |
| type | int | Type de graphique [ChartType](../../com.aspose.slides/charttype) |

**Renvoie:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nouvelle série de graphique [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Crée une nouvelle série de graphique à partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) et l'ajoute à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cellule contenant le nom de la série. |
| type | int | Type de la série |

--------------------

Si une série de graphique créée à partir de la même cellule existe déjà dans la collection, la méthode n'ajoute rien et renvoie son index. |

**Renvoie:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de graphique ajoutée ou série déjà présente dans la collection.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Crée une nouvelle série de graphique à partir de [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) et l'ajoute à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Cellules contenant le nom de la série. |
| type | int | Type de la série |

--------------------

Si une série de graphique créée à partir de la même cellule existe déjà dans la collection, la méthode n'ajoute rien et renvoie son index. |

**Renvoie:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de graphique ajoutée ou série déjà présente dans la collection.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Crée une nouvelle série de graphique à partir d'une valeur et l'ajoute à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la série. |
| type | int | Type de la série |

**Renvoie:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de graphique ajoutée.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Recherche le [IChartSeries](../../com.aspose.slides/ichartseries) spécifié et renvoie l'index de base zéro de la première occurrence dans l'ensemble de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valeur de la série de graphique. |

**Renvoie:**
int - L'index de base zéro de la première occurrence de la valeur dans la collection, si trouvé ; sinon -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Supprime la valeur spécifiée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | La valeur. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime l'élément à l'index spécifié

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les éléments (y compris le style du graphique) de la collection.