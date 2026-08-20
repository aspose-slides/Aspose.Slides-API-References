---
title: ChartCategory
second_title: Aspose.Slides for Java API 參考
description: 表示圖表類別。
type: docs
url: /zh-hant/com.aspose.slides/chartcategory/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

表示圖表類別。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getUseCell()](#getUseCell--) | 如果 true，則 AsCell 屬性為實際值。 |
| [getAsCell()](#getAsCell--) | 返回或設定 IChartDataCell 物件。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 返回或設定 IChartDataCell 物件。 |
| [getAsLiteral()](#getAsLiteral--) | 返回或設定 AsLiteral 物件。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | 返回或設定 AsLiteral 物件。 |
| [getValue()](#getValue--) | 如果 UseCell 為 true，則此屬性表示 AsCell.Value 屬性。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 如果 UseCell 為 true，則此屬性表示 AsCell.Value 屬性。 |
| [getGroupingLevels()](#getGroupingLevels--) | 受管理的容器，包含圖表類別分組層級的值。 |
| [remove()](#remove--) | 從圖表中移除類別。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


如果 true，則 AsCell 屬性為實際值。換句話說，工作表用於存儲類別（此情況支援多層類別）。如果 false，則 AsLiteral 屬性為實際值。換句話說，工作表不會用於存儲類別（此情況不支援多層類別）。唯讀 boolean。

若要變更此屬性的值（對集合中的所有類別），請將新值設定至 ChartCategoryCollection.UseCells 屬性。

**返回值:** boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


返回或設定 IChartDataCell 物件。如果類別是多層的，則使用層級 "0" 的 IChartDataCell 物件。可讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**返回值:** [IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


返回或設定 IChartDataCell 物件。如果類別是多層的，則使用層級 "0" 的 IChartDataCell 物件。可讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


返回或設定 AsLiteral 物件。可讀寫 Object。

**返回值:** java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


返回或設定 AsLiteral 物件。可讀寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```


如果 UseCell 為 true，則此屬性表示 AsCell.Value 屬性。如果 UseCell 為 false，則此屬性表示 AsLiteral 屬性。可讀寫 Object。

**返回值:** java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


如果 UseCell 為 true，則此屬性表示 AsCell.Value 屬性。如果 UseCell 為 false，則此屬性表示 AsLiteral 屬性。可讀寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```


受管理的容器，包含圖表類別分組層級的值。多層類別包含多個分組層級。分組層級的索引從零開始。唯讀 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**返回值:** [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```


從圖表中移除類別。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回值:** com.aspose.slides.IDOMObject