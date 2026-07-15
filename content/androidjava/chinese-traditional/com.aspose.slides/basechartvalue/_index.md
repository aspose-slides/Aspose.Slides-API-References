---
title: BaseChartValue
second_title: Aspose.Slides for Android via Java API 參考
description: 表示圖表的值。
type: docs
url: /zh-hant/com.aspose.slides/basechartvalue/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

表示圖表的值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 指定後代中 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 屬性是否有效。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 指定後代中 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 屬性是否有效。 |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

指定後代中 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 屬性是否有效。換言之，它指定 Data 屬性的值類型。可讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

對於 ChartDataPointCollection 中的點，此屬性為唯讀。在此情況下，要變更此屬性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 屬性之一。

**返回值：**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

指定後代中 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 屬性是否有效。換言之，它指定 Data 屬性的值類型。可讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

對於 ChartDataPointCollection 中的點，此屬性為唯讀。在此情況下，要變更此屬性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 屬性之一。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Data. 可讀寫 Object.

**返回值：**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. 可讀寫 Object.

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject