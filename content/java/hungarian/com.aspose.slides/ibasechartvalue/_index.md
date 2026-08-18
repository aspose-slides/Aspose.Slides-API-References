---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
url: /hu/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

A diagram egy értékét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Megadja, hogy az AsCell vagy az AsLiteralString vagy az AsLiteralDouble tulajdonság valós-e. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Megadja, hogy az AsCell vagy az AsLiteralString vagy az AsLiteralDouble tulajdonság valós-e. |
| [getData()](#getData--) | Olvasás/írás Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Olvasás/írás Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Megadja, hogy az AsCell vagy az AsLiteralString vagy az AsLiteralDouble tulajdonság valós-e. Más szóval meghatározza a Data tulajdonság értékének típusát. Ez a tulajdonság csak olvasható. A tulajdonos értékének megváltoztatásához használhatja a ChartDataPointCollection.DataSourceTypeFor<...> tulajdonságok egyikét. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Visszatérési érték:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Megadja, hogy az AsCell vagy az AsLiteralString vagy az AsLiteralDouble tulajdonság valós-e. Más szóval meghatározza a Data tulajdonság értékének típusát. Ez a tulajdonság csak olvasható. A tulajdonos értékének megváltoztatásához használhatja a ChartDataPointCollection.DataSourceTypeFor<...> tulajdonságok egyikét. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Olvasás/írás Object.

**Visszatérési érték:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |