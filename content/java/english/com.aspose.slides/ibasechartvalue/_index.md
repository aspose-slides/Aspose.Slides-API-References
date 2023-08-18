---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
weight: 654
url: /com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Represents a value of a chart.
## Methods

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual. |
| [getData()](#getData--) | Read/write Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Read/write Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual. In other words it specifies the type of value of the Data property. This property is read-only. For changing value of this property you can use one of the ChartDataPointCollection.DataSourceTypeFor<...> properties. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Returns:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual. In other words it specifies the type of value of the Data property. This property is read-only. For changing value of this property you can use one of the ChartDataPointCollection.DataSourceTypeFor<...> properties. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Read/write Object.

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Read/write Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

