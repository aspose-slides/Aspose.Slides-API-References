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

代表圖表類別。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getUseCell()](#getUseCell--) | 如果為 true，則 AsCell 屬性為有效。 |
| [getAsCell()](#getAsCell--) | 傳回或設定 IChartDataCell 物件。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 傳回或設定 IChartDataCell 物件。 |
| [getAsLiteral()](#getAsLiteral--) | 傳回或設定 AsLiteral 物件。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | 傳回或設定 AsLiteral 物件。 |
| [getValue()](#getValue--) | 如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。 |
| [getGroupingLevels()](#getGroupingLevels--) | 受管理的圖表類別分組層級之值的容器。 |
| [getCachedValue()](#getCachedValue--) | 取得圖表類別的快取值。 |
| [remove()](#remove--) | 從圖表中移除類別。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

如果為 true，則 AsCell 屬性為有效。換句話說，工作表用於儲存類別（此情況支援多層類別）。如果為 false，則 AsLiteral 屬性為有效。換句話說，工作表未用於儲存類別（且此情況不支援多層類別）。唯讀 boolean。

--------------------

若要變更此屬性的值（針對集合中的所有類別），請將新值設定至 ChartCategoryCollection.UseCells 屬性。

**傳回:**  
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

傳回或設定 IChartDataCell 物件。如果類別是多層級，則使用等級 "0" 的 IChartDataCell 物件。讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**傳回:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

傳回或設定 IChartDataCell 物件。如果類別是多層級，則使用等級 "0" 的 IChartDataCell 物件。讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

傳回或設定 AsLiteral 物件。讀寫 Object。

**傳回:**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

傳回或設定 AsLiteral 物件。讀寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。如果 UseCell 為 false，則此屬性代表 AsLiteral 屬性。讀寫 Object。

**傳回:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

如果 UseCell 為 true，則此屬性代表 AsCell.Value 屬性。如果 UseCell 為 false，則此屬性代表 AsLiteral 屬性。讀寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

受管理的圖表類別分組層級之值的容器。多層類別包含超過一個分組層級。分組層級的索引從零開始。唯讀 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**傳回:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

取得圖表類別的快取值。唯讀 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // 列印所有快取的圖表類別值。
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```

**傳回:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### remove() {#remove--}
```
public final void remove()
```

從圖表中移除類別。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**  
com.aspose.slides.IDOMObject