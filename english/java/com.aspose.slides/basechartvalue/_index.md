---
title: BaseChartValue
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a value of a chart.
type: docs
weight: 37
url: /java/com.aspose.slides/basechartvalue/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Represents a value of a chart.
## Constructors

| Constructor | Description |
| --- | --- |
| [BaseChartValue(IDOMObject parentImmediate, DataSourceTypeHolder dataSourceTypeHolder, boolean centralizedTypeChangingRestriction)](#BaseChartValue-com.aspose.slides.IDOMObject-com.aspose.slides.DataSourceTypeHolder-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble property is actual in descendants. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble property is actual in descendants. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### BaseChartValue(IDOMObject parentImmediate, DataSourceTypeHolder dataSourceTypeHolder, boolean centralizedTypeChangingRestriction) {#BaseChartValue-com.aspose.slides.IDOMObject-com.aspose.slides.DataSourceTypeHolder-boolean-}
```
 BaseChartValue(IDOMObject parentImmediate, DataSourceTypeHolder dataSourceTypeHolder, boolean centralizedTypeChangingRestriction)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| dataSourceTypeHolder | com.aspose.slides.DataSourceTypeHolder |  |
| centralizedTypeChangingRestriction | boolean | 1) If true then DataSourceType depends on dataSourceTypeHolder whitch is passed as parameter into constructor. And there is no other way to change DataSourceType but to change DataSourceTypeHolder.DataSourceType value. And if one dataSourceTypeHolder is passed to multiple BaseChartValue instances then it is the way to centralized managing of type of multiple BaseChartValue-values. 2) If false then it is possible to change DataSourceType. |

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
