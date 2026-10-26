---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: 表示圖表類別。
type: docs
url: /zh-hant/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

表示圖表類別。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getUseCell()](#getUseCell--) | If true then AsCell property is actual. |
| [getAsCell()](#getAsCell--) | Returns or sets IChartDataCell object. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets IChartDataCell object. |
| [getAsLiteral()](#getAsLiteral--) | Returns or sets AsLiteral if UseCell is false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returns or sets AsLiteral if UseCell is false. |
| [getValue()](#getValue--) | If UseCell is true then this property represents AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | If UseCell is true then this property represents AsCell.Value property. |
| [getGroupingLevels()](#getGroupingLevels--) | Managed container of the values of the chart category grouping levels. |
| [remove()](#remove--) | Removes category from chart. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

如果為 true，則 AsCell 屬性為實際使用的屬性。換句話說，工作表用於儲存類別（此情況支援多層類別）。如果為 false，則 AsLiteral 屬性為實際使用的屬性。換句話說，工作表 **不** 用於儲存類別（此情況不支援多層類別）。唯讀布林值。

--------------------

若要變更此屬性的值（針對集合中的所有類別），請將新值設定至 [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) 屬性。

**傳回：**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

傳回或設定 IChartDataCell 物件。如果類別是多層次的，則使用層級 "0" 的 IChartDataCell 物件。可讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**傳回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

傳回或設定 IChartDataCell 物件。如果類別是多層次的，則使用層級 "0" 的 IChartDataCell 物件。可讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

傳回或設定 AsLiteral，如果 UseCell 為 false。可讀寫 Object。

**傳回：**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

傳回或設定 AsLiteral，如果 UseCell 為 false。可讀寫 Object。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。如果 UseCell 為 false，則此屬性代表 AsLiteral 屬性。可讀寫 Object。

**傳回：**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。如果 UseCell 為 false，則此屬性代表 AsLiteral 屬性。可讀寫 Object。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Managed container of the values of the chart category grouping levels. Multi-level category contain more then one grouping level. Grouping levels indexing is zero-based. Read-only [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**傳回：**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Removes category from chart。