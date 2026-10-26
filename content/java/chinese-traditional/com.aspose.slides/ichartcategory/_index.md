---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /zh-hant/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

代表圖表類別。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getUseCell()](#getUseCell--) | 如果為 true，則 AsCell 屬性為實際值。 |
| [getAsCell()](#getAsCell--) | 傳回或設定 IChartDataCell 物件。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 傳回或設定 IChartDataCell 物件。 |
| [getAsLiteral()](#getAsLiteral--) | 如果 UseCell 為 false，則傳回或設定 AsLiteral。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | 如果 UseCell 為 false，則傳回或設定 AsLiteral。 |
| [getValue()](#getValue--) | 如果 UseCell 為 true，則此屬性表示 AsCell.Value 屬性。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 如果 UseCell 為 true，則此屬性表示 AsCell.Value 屬性。 |
| [getGroupingLevels()](#getGroupingLevels--) | 圖表類別分組層級值的受管理容器。 |
| [remove()](#remove--) | 從圖表中移除類別。 |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

如果為 true，則 AsCell 屬性為實際值。換句話說，工作表用於儲存類別（此情況支援多層級類別）。如果為 false，則 AsLiteral 屬性為實際值。換句話說，工作表 **不** 用於儲存類別（且此情況不支援多層級類別）。唯讀布林值。

--------------------

若要變更此屬性的值（對集合中的所有類別），請將新值設定至 [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) 屬性。

**傳回:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

傳回或設定 IChartDataCell 物件。如果類別為多層級，則使用層級「0」的 IChartDataCell 物件。可讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**傳回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

傳回或設定 IChartDataCell 物件。如果類別為多層級，則使用層級「0」的 IChartDataCell 物件。可讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

如果 UseCell 為 false，則傳回或設定 AsLiteral。可讀寫 Object。

**傳回:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

如果 UseCell 為 false，則傳回或設定 AsLiteral。可讀寫 Object。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

如果 UseCell 為 true，則此屬性表示 AsCell.Value 屬性。如果 UseCell 為 false，則此屬性表示 AsLiteral 屬性。可讀寫 Object。

**傳回:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

如果 UseCell 為 true，則此屬性表示 AsCell.Value 屬性。如果 UseCell 為 false，則此屬性表示 AsLiteral 屬性。可讀寫 Object。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

受管理的圖表類別分組層級值容器。多層級類別包含多於一個分組層級。分組層級索引是從零開始。唯讀 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**傳回:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

從圖表中移除類別。