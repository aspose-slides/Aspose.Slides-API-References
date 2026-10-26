---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
url: /fr/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Représente une valeur d'un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Indique si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Indique si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective. |
| [getData()](#getData--) | Lecture/écriture Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Lecture/écriture Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Indique si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective. En d'autres termes, cela spécifie le type de valeur de la propriété Data. Cette propriété est en lecture seule. Pour changer la valeur de cette propriété, vous pouvez utiliser l'une des propriétés ChartDataPointCollection.DataSourceTypeFor<...>. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Retour:**  
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Indique si la propriété AsCell ou AsLiteralString ou AsLiteralDouble est effective. En d'autres termes, cela spécifie le type de valeur de la propriété Data. Cette propriété est en lecture seule. Pour changer la valeur de cette propriété, vous pouvez utiliser l'une des propriétés ChartDataPointCollection.DataSourceTypeFor<...>. Lecture/écriture [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Lecture/écriture Object.

**Retour:**  
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Lecture/écriture Object.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |