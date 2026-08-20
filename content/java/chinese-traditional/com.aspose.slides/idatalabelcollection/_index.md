---
title: IDataLabelCollection
second_title: Aspose.Slides for Java API 參考
description: 表示系列標籤。
type: docs
url: /zh-hant/com.aspose.slides/idatalabelcollection/
---
**已實作的介面:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

表示系列標籤。

## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得具有指定索引之資料點的資料標籤。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 傳回集合中所有資料標籤的預設格式。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | 表示資料標籤引導線的格式。 |
| [isVisible()](#isVisible--) | False 表示資料標籤預設為不可見（因此 DefaultDataLabelFormat 屬性的所有 Show\*-flags (ShowValue, ...) 為 false）。 |
| [hide()](#hide--) | 透過將 DefaultDataLabelFormat 屬性的所有 Show\*-flags (ShowValue, ...) 設定為 false 狀態，使資料標籤預設為隱藏。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 取得集合中可見資料標籤的數量。 |
| [getCount()](#getCount--) | 取得集合中所有資料標籤的數量。 |
| [getParentSeries()](#getParentSeries--) | 傳回父圖表系列。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 傳回集合中指定 DataLabel 的索引。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

取得具有指定索引之資料點的資料標籤。

--------------------

存取資料標籤的替代方式為： - getSeries().getDataPoints().get\_Item(i).getLabel() - 管理標籤屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

傳回集合中所有資料標籤的預設格式。唯讀 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**傳回值：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

表示資料標籤引導線的格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回值：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False 表示資料標籤預設為不可見（因此 DefaultDataLabelFormat 屬性的所有 Show\*-flags (ShowValue, ...) 為 false）。唯讀 boolean。

--------------------

若資料標籤預設為可見，您可以使用 Hide() 方法將其預設隱藏。若資料標籤預設為不可見 (IsVisible 為 false)，您可以透過將 DefaultDataLabelFormat 屬性的 Show\*-flags (ShowValue, ...) 設定為 true，將資料標籤設為「預設可見」。

**傳回值：**
boolean

### hide() {#hide--}
```
public abstract void hide()
```

透過將 DefaultDataLabelFormat 屬性的所有 Show\*-flags (ShowValue, ...) 設定為 false，使資料標籤預設為隱藏。之後 IsVisible 會為 false。

--------------------

若資料標籤預設為不可見 (IsVisible 為 false)，您可以透過將 DefaultDataLabelFormat 屬性的 Show\*-flags (ShowValue, ...) 設定為 true，使資料標籤「預設可見」。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

取得集合中可見資料標籤的數量。唯讀 int 。

**傳回值：**
int

### getCount() {#getCount--}
```
public abstract int getCount()
```

取得集合中所有資料標籤的數量。唯讀 int 。

**傳回值：**
int

### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

傳回父圖表系列。唯讀 [IChartSeries](../../com.aspose.slides/ichartseries)。

**傳回值：**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

傳回集合中指定 DataLabel 的索引。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 要尋找的 DataLabel。 |

**傳回值：**
int - DataLabel 的索引，若 DataLabel 不屬於此集合則回傳 -1.