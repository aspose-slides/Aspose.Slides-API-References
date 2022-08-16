---
title: BaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents a value of a chart.
type: docs
weight: 37
url: /androidjava/com.aspose.slides/basechartvalue/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Represents a value of a chart.
## Methods

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble property is actual in descendants. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble property is actual in descendants. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble property is actual in descendants. In other words it specifies the type of value of the Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

For points in ChartDataPointCollection this property is read-only. In this case for changing value of this property you can use one of the ChartDataPointCollection.DataSourceTypeFor<...> properties.

**Returns:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```


Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble property is actual in descendants. In other words it specifies the type of value of the Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

For points in ChartDataPointCollection this property is read-only. In this case for changing value of this property you can use one of the ChartDataPointCollection.DataSourceTypeFor<...> properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Data. Read/write Object.

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Data. Read/write Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
