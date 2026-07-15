---
title: ChartCategory
second_title: Aspose.Slides for Android via Java API 參考
description: 代表圖表類別。
type: docs
url: /zh-hant/com.aspose.slides/chartcategory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

代表圖表類別。
## Methods

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | If true then AsCell property is actual. |
| [getAsCell()](#getAsCell--) | Returns or sets IChartDataCell object. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets IChartDataCell object. |
| [getAsLiteral()](#getAsLiteral--) | Returns or sets AsLiteral object. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returns or sets AsLiteral object. |
| [getValue()](#getValue--) | If UseCell is true then this property represents AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | If UseCell is true then this property represents AsCell.Value property. |
| [getGroupingLevels()](#getGroupingLevels--) | Managed container of the values of the chart category grouping levels. |
| [remove()](#remove--) | Removes category from chart. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

如果為 true，則 AsCell 屬性為實際使用的屬性。換句話說，工作表用於儲存類別（此情況支援多層級類別）。如果為 false，則 AsLiteral 屬性為實際使用的屬性。換句話說，工作表 **不** 用於儲存類別（此情況不支援多層級類別）。唯讀布林值。

--------------------

若要變更此屬性的值（對集合中所有類別），請將新值設定至 ChartCategoryCollection.UseCells 屬性。

**Returns:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Returns or sets AsLiteral object. Read/write Object.

**Returns:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Returns or sets AsLiteral object. Read/write Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Managed container of the values of the chart category grouping levels. Multi-level category contain more then one grouping level. Grouping levels indexing is zero-based. Read-only [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Returns:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Removes category from chart.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject