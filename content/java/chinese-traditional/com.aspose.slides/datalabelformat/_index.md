---
title: DataLabelFormat
second_title: Aspose.Slides for Java API 參考
description: 表示 DataLabel 的格式化選項。
type: docs
url: /zh-hant/com.aspose.slides/datalabelformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已實作的介面：**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

表示 DataLabel 的格式化選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 可讀寫 boolean。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 可讀寫 boolean。 |
| [getNumberFormat()](#getNumberFormat--) | 表示 DataLabels 物件的格式字串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 表示 DataLabels 物件的格式字串。 |
| [getFormat()](#getFormat--) | 表示資料標籤的格式。 |
| [getPosition()](#getPosition--) | 表示資料標籤的位置。 |
| [setPosition(int value)](#setPosition-int-) | 表示資料標籤的位置。 |
| [getShowLegendKey()](#getShowLegendKey--) | 表示指定圖表的資料標籤圖例鍵顯示行為。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 表示指定圖表的資料標籤圖例鍵顯示行為。 |
| [getShowValue()](#getShowValue--) | 表示指定圖表的資料標籤百分比值顯示行為。 |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 表示指定圖表的資料標籤百分比值顯示行為。 |
| [getShowCategoryName()](#getShowCategoryName--) | 表示指定圖表的資料標籤類別名稱顯示行為。 |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 表示指定圖表的資料標籤類別名稱顯示行為。 |
| [getShowSeriesName()](#getShowSeriesName--) | 傳回或設定 Boolean，以指示圖表上資料標籤的系列名稱顯示行為。 |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | 傳回或設定 Boolean，以指示圖表上資料標籤的系列名稱顯示行為。 |
| [getShowPercentage()](#getShowPercentage--) | 表示指定圖表的資料標籤百分比值顯示行為。 |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 表示指定圖表的資料標籤百分比值顯示行為。 |
| [getShowBubbleSize()](#getShowBubbleSize--) | 表示指定圖表的資料標籤氣泡大小值顯示行為。 |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 表示指定圖表的資料標籤氣泡大小值顯示行為。 |
| [getShowLeaderLines()](#getShowLeaderLines--) | 表示指定圖表的資料標籤引線顯示行為。 |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 表示指定圖表的資料標籤引線顯示行為。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 表示指定圖表的資料標籤儲存格值顯示行為。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 表示指定圖表的資料標籤儲存格值顯示行為。 |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 決定指定圖表的資料標籤是顯示為資料標註還是資料標籤。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 決定指定圖表的資料標籤是顯示為資料標註還是資料標籤。 |
| [getSeparator()](#getSeparator--) | 設定或傳回 Variant，表示圖表上資料標籤使用的分隔符號。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | 設定或傳回 Variant，表示圖表上資料標籤使用的分隔符號。 |
| [getTextFormat()](#getTextFormat--) | 傳回圖表文字格式。 |
| [getChart()](#getChart--) | 傳回圖表。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Read-only long.

**傳回：**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

可讀寫 boolean.

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 IsNumberFormatLinkedToSource 屬性的預設值。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 IsNumberFormatLinkedToSource 屬性（例如「DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);」會使所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等於該值）。

**傳回：**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

可讀寫 boolean.

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 IsNumberFormatLinkedToSource 屬性的預設值。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 IsNumberFormatLinkedToSource 屬性（例如「DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);」會使所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等於該值）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

表示 DataLabels 物件的格式字串。可讀寫 String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 NumberFormat 屬性的預設值。設定此屬性時，該值也會同時設定給 DataLabelCollection 中所有資料標籤的 NumberFormat 屬性（例如「DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);」會使所有 DataLabels.get_Item(i).getNumberFormat() 等於該值）。

**傳回：**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

表示 DataLabels 物件的格式字串。可讀寫 String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 NumberFormat 屬性的預設值。設定此屬性時，該值也會同時設定給 DataLabelCollection 中所有資料標籤的 NumberFormat 屬性（例如「DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);」會使所有 DataLabels.get_Item(i).getNumberFormat() 等於該值）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示資料標籤的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性表示新資料標籤的預設格式。

**傳回：**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

表示資料標籤的位置。可讀寫 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 Position 屬性的預設值。此屬性表示 DataLabel 物件的位置。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 Position 屬性（例如「DataLabels.getDefaultDataLabelFormat().setPosition(val);」會使所有 DataLabels.get_Item(i).getPosition() 等於該值）。

**傳回：**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

表示資料標籤的位置。可讀寫 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 Position 屬性的預設值。此屬性表示 DataLabel 物件的位置。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 Position 屬性（例如「DataLabels.getDefaultDataLabelFormat().setPosition(val);」會使所有 DataLabels.get_Item(i).getPosition() 等於該值）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

表示指定圖表的資料標籤圖例鍵顯示行為。如果資料標籤圖例鍵可見則為 true。可讀寫 boolean。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLegendKey 屬性的預設值。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLegendKey 屬性（例如「DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);」會使所有 DataLabels.get_Item(i).getShowLegendKey() 等於該值）。

**傳回：**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

表示指定圖表的資料標籤圖例鍵顯示行為。如果資料標籤圖例鍵可見則為 true。可讀寫 boolean。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLegendKey 屬性的預設值。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLegendKey 屬性（例如「DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);」會使所有 DataLabels.get_Item(i).getShowLegendKey() 等於該值）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

表示指定圖表的資料標籤百分比值顯示行為。True 表示顯示百分比值，False 表示隱藏。可讀寫 boolean。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowValue 屬性的預設值。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowValue 屬性（例如「DataLabels.getDefaultDataLabelFormat().setShowValue(val);」會使所有 DataLabels.get_Item(i).getShowValue() 等於該值）。

**傳回：**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

表示指定圖表的資料標籤百分比值顯示行為。True 表示顯示百分比值，False 表示隱藏。可讀寫 boolean。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowValue 屬性的預設值。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowValue 屬性（例如「DataLabels.getDefaultDataLabelFormat().setShowValue(val);」會使所有 DataLabels.get_Item(i).getShowValue() 等於該值）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

表示指定圖表的資料標籤類別名稱顯示行為。True 為顯示圖表上資料標籤的類別名稱，False 為隱藏。可讀寫 boolean。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowCategoryName 屬性的預設值。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowCategoryName 屬性（例如「DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);」會使所有 DataLabels.get_Item(i).getShowCategoryName() 等於該值）。

**傳回：**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

表示指定圖表的資料標籤類別名稱顯示行為。True 為顯示圖表上資料標籤的類別名稱，False 為隱藏。可讀寫 boolean。

--------------------

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowCategoryName 屬性的預設值。以值設定此屬性時，同時會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowCategoryName 屬性（例如「DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);」會使所有 DataLabels.get_Item(i).getShowCategoryName() 等於該值）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowCategoryName 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowCategoryName 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 會導致所有 DataLabels.get_Item(i).getShowCategoryName() 等於 val）。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

傳回或設定布林值，以指示圖表上資料標籤的系列名稱顯示行為。True 表示顯示系列名稱。False 表示隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowSeriesName 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowSeriesName 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 會導致所有 DataLabels.get_Item(i).getShowSeriesName() 等於 val）。

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

傳回或設定布林值，以指示圖表上資料標籤的系列名稱顯示行為。True 表示顯示系列名稱。False 表示隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowSeriesName 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowSeriesName 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 會導致所有 DataLabels.get_Item(i).getShowSeriesName() 等於 val）。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

表示指定圖表的資料標籤百分比值顯示行為。True 會顯示百分比值。False 會隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowPercentage 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowPercentage 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 會導致所有 DataLabels.get_Item(i).getShowPercentage() 等於 val）。

**傳回：**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

表示指定圖表的資料標籤百分比值顯示行為。True 會顯示百分比值。False 會隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowPercentage 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowPercentage 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 會導致所有 DataLabels.get_Item(i).getShowPercentage() 等於 val）。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

表示指定圖表的資料標籤泡泡大小值顯示行為。True 會顯示泡泡大小值。False 會隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowBubbleSize 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowBubbleSize 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 會導致所有 DataLabels.get_Item(i).getShowBubbleSize() 等於 val）。

**傳回：**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

表示指定圖表的資料標籤泡泡大小值顯示行為。True 會顯示泡泡大小值。False 會隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowBubbleSize 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowBubbleSize 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 會導致所有 DataLabels.get_Item(i).getShowBubbleSize() 等於 val）。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

表示指定圖表的資料標籤引線顯示行為。True 會顯示引線。False 會隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowLeaderLines 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowLeaderLines 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 會導致所有 DataLabels.get_Item(i).getShowLeaderLines() 等於 val）。

**傳回：**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

表示指定圖表的資料標籤引線顯示行為。True 會顯示引線。False 會隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowLeaderLines 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowLeaderLines 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 會導致所有 DataLabels.get_Item(i).getShowLeaderLines() 等於 val）。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

表示指定圖表的資料標籤儲存格值顯示行為。True 會顯示儲存格值。False 會隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelValueFromCell 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelValueFromCell 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 會導致所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等於 val）。

**傳回：**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

表示指定圖表的資料標籤儲存格值顯示行為。True 會顯示儲存格值。False 會隱藏。讀寫布林。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelValueFromCell 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelValueFromCell 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 會導致所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等於 val）。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

決定指定圖表的資料標籤是顯示為資料呼叫框還是顯示為資料標籤。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelAsDataCallout 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelAsDataCallout 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 會導致所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等於 val）。

**傳回：**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

決定指定圖表的資料標籤是顯示為資料呼叫框還是顯示為資料標籤。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelAsDataCallout 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelAsDataCallout 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 會導致所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等於 val）。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

設定或傳回一個 Variant，表示圖表上資料標籤使用的分隔符號。讀寫 String。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 Separator 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 Separator 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 會導致所有 DataLabels.get_Item(i).getSeparator() 等於 val）。

**傳回：**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

設定或傳回一個 Variant，表示圖表上資料標籤使用的分隔符號。讀寫 String。

--------------------

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 Separator 屬性的預設值。將此屬性設定為某個值時，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 Separator 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 會導致所有 DataLabels.get_Item(i).getSeparator() 等於 val）。
**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

傳回圖表文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**回傳：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

傳回圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**回傳：**
[IChart](../../com.aspose.slides/ichart)