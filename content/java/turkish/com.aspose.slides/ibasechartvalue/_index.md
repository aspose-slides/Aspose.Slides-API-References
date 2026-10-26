---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
url: /tr/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Represents a value of a chart.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | AsCell, AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | AsCell, AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [getData()](#getData--) | Okuma/Yazma Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Okuma/Yazma Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


AsCell, AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Diğer bir deyişle, Data özelliğinin değer tipini belirtir. Bu özellik yalnızca okunabilir. Bu özelliğin değerini değiştirmek için ChartDataPointCollection.DataSourceTypeFor<...> özelliklerinden birini kullanabilirsiniz. Okuma/Yazma [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Döndürür:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


AsCell, AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Diğer bir deyişle, Data özelliğinin değer tipini belirtir. Bu özellik yalnızca okunabilir. Bu özelliğin değerini değiştirmek için ChartDataPointCollection.DataSourceTypeFor<...> özelliklerinden birini kullanabilirsiniz. Okuma/Yazma [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Okuma/Yazma Object.

**Döndürür:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Okuma/Yazma Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |