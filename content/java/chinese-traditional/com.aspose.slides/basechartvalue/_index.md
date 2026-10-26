---
title: BaseChartValue
second_title: Aspose.Slides for Java API 參考
description: 表示圖表的值。
type: docs
url: /zh-hant/com.aspose.slides/basechartvalue/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

表示圖表的值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 指定 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 屬性在衍生類別中是否有效。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 指定 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 屬性在衍生類別中是否有效。 |
| [getData()](#getData--) | 資料。 |
| [setData(Object value)](#setData-java.lang.Object-) | 資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

指定 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 屬性在衍生類別中是否有效。換句話說，它指定 Data 屬性的值類型。可讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

對於 ChartDataPointCollection 中的點，此屬性為唯讀。在此情況下，若要變更此屬性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 屬性之一。

**回傳:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

指定 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 屬性在衍生類別中是否有效。換句話說，它指定 Data 屬性的值類型。可讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

對於 ChartDataPointCollection 中的點，此屬性為唯讀。在此情況下，若要變更此屬性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 屬性之一。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

資料。可讀寫 Object。

**回傳:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

資料。可讀寫 Object。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

回傳 Parent_Immediate 物件。唯讀 IDOMObject。