---
title: IBaseChartValue
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A diagram egy értékét képviseli.
type: docs
url: /hu/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

A diagram egy értékét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Megadja, hogy az AsCell vagy az AsLiteralString vagy az AsLiteralDouble tulajdonság a tényleges. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Megadja, hogy az AsCell vagy az AsLiteralString vagy az AsLiteralDouble tulajdonság a tényleges. |
| [getData()](#getData--) | Olvasás/írás Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Olvasás/írás Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Megadja, hogy az AsCell vagy az AsLiteralString vagy az AsLiteralDouble tulajdonság a tényleges. Más szóval meghatározza a Data tulajdonság értékének típusát. Ez a tulajdonság csak olvasható. A tulajdonság értékének módosításához használhatja a ChartDataPointCollection.DataSourceTypeFor<...> tulajdonságok egyikét. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Returns:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Megadja, hogy az AsCell vagy az AsLiteralString vagy az AsLiteralDouble tulajdonság a tényleges. Más szóval meghatározza a Data tulajdonság értékének típusát. Ez a tulajdonság csak olvasható. A tulajdonság értékének módosításához használhatja a ChartDataPointCollection.DataSourceTypeFor<...> tulajdonságok egyikét. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Olvasás/írás Object.

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Olvasás/írás Object.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |