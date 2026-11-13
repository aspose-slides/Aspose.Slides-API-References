---
title: IChartCategory
second_title: Aspose.Slides 的 Java API 參考
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
| [getUseCell()](#getUseCell--) | 如果為 true，則 AsCell 屬性為實際值。 |
| [getAsCell()](#getAsCell--) | 傳回或設定 IChartDataCell 物件。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 傳回或設定 IChartDataCell 物件。 |
| [getAsLiteral()](#getAsLiteral--) | 傳回或設定 AsLiteral（當 UseCell 為 false 時）。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | 傳回或設定 AsLiteral（當 UseCell 為 false 時）。 |
| [getValue()](#getValue--) | 如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。 |
| [getCachedValue()](#getCachedValue--) | 取得圖表類別的快取值。 |
| [getGroupingLevels()](#getGroupingLevels--) | 受管理的容器，用於存放圖表類別分組層級的值。 |
| [remove()](#remove--) | 從圖表中移除類別。 |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


如果為 true，則 AsCell 屬性為實際值。換句話說，工作表用於儲存類別（此情況支援多層類別）。如果為 false，則 AsLiteral 屬性為實際值。換句話說，工作表不會用於儲存類別（此情況不支援多層類別）。唯讀 boolean。

--------------------

若要變更此屬性的值（對集合中的所有類別），請將新值設定至 [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) 屬性。

**返回值：**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


傳回或設定 IChartDataCell 物件。若類別為多層級，則使用層級 "0" 的 IChartDataCell 物件。讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**返回值：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


傳回或設定 IChartDataCell 物件。若類別為多層級，則使用層級 "0" 的 IChartDataCell 物件。讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


傳回或設定 AsLiteral（當 UseCell 為 false 時）。讀寫 Object。

**返回值：**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


傳回或設定 AsLiteral（當 UseCell 為 false 時）。讀寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。若 UseCell 為 false，則此屬性代表 AsLiteral 屬性。讀寫 Object。

**返回值：**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。若 UseCell 為 false，則此屬性代表 AsLiteral 屬性。讀寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


取得圖表類別的快取值。唯讀 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // 列印所有快取的圖表類別值。
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


受管理的容器，用於存放圖表類別分組層級的值。多層類別包含多於一個分組層級。分組層級索引為零基。唯讀 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**返回值：**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


從圖表中移除類別。