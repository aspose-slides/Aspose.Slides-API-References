---
title: BaseChartValue
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une valeur d'un graphique.
type: docs
url: /fr/com.aspose.slides/basechartvalue/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Représente une valeur d'un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Spécifie si la propriété AsCell, AsCells, AsLiteralString ou AsLiteralDouble est effective chez les descendants. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Spécifie si la propriété AsCell, AsCells, AsLiteralString ou AsLiteralDouble est effective chez les descendants. |
| [getData()](#getData--) | Données. |
| [setData(Object value)](#setData-java.lang.Object-) | Données. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Spécifie si la propriété AsCell, AsCells, AsLiteralString ou AsLiteralDouble est effective chez les descendants. En d'autres termes, cela spécifie le type de valeur de la propriété Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Pour les points dans ChartDataPointCollection, cette propriété est en lecture seule. Dans ce cas, pour modifier la valeur de cette propriété, vous pouvez utiliser l'une des propriétés ChartDataPointCollection.DataSourceTypeFor<...>.

**Renvoie :**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```


Spécifie si la propriété AsCell, AsCells, AsLiteralString ou AsLiteralDouble est effective chez les descendants. En d'autres termes, cela spécifie le type de valeur de la propriété Data. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Pour les points dans ChartDataPointCollection, cette propriété est en lecture seule. Dans ce cas, pour modifier la valeur de cette propriété, vous pouvez utiliser l'une des propriétés ChartDataPointCollection.DataSourceTypeFor<...>.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Données. Lecture/écriture Object.

**Renvoie :**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Données. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject