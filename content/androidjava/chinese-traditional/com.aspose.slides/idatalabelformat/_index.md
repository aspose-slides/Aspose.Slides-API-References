---
title: IDataLabelFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 代表 DataLabel 的格式設定選項。
type: docs
url: /zh-hant/com.aspose.slides/idatalabelformat/
---
**已實作的介面:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

表示 DataLabel 的格式設定選項。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 可讀寫布林值。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 可讀寫布林值。 |
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
| [getShowSeriesName()](#getShowSeriesName--) | 傳回或設定布林值以指示圖表上資料標籤的系列名稱顯示行為。 |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | 傳回或設定布林值以指示圖表上資料標籤的系列名稱顯示行為。 |
| [getShowPercentage()](#getShowPercentage--) | 表示指定圖表的資料標籤百分比值顯示行為。 |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 表示指定圖表的資料標籤百分比值顯示行為。 |
| [getShowBubbleSize()](#getShowBubbleSize--) | 表示指定圖表的資料標籤氣泡大小值顯示行為。 |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 表示指定圖表的資料標籤氣泡大小值顯示行為。 |
| [getShowLeaderLines()](#getShowLeaderLines--) | 表示指定圖表的資料標籤引線顯示行為。 |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 表示指定圖表的資料標籤引線顯示行為。 |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 決定指定圖表的資料標籤將顯示為資料註解或資料標籤。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 決定指定圖表的資料標籤將顯示為資料註解或資料標籤。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 表示指定圖表的資料標籤儲存格值顯示行為。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 表示指定圖表的資料標籤儲存格值顯示行為。 |
| [getSeparator()](#getSeparator--) | 設定或傳回表示圖表上資料標籤使用之分隔符的 Variant。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | 設定或傳回表示圖表上資料標籤使用之分隔符的 Variant。 |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 IsNumberFormatLinkedToSource 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 IsNumberFormatLinkedToSource 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" 會使所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等於 val）。

**傳回值:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 IsNumberFormatLinkedToSource 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 IsNumberFormatLinkedToSource 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" 會使所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

表示 DataLabels 物件的格式字串。可讀寫 String。

--------------------

> ``` 
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 NumberFormat 屬性的預設值。以值設定此屬性時，該值也會設定給 DataLabelCollection 中所有資料標籤的 NumberFormat 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" 會使所有 DataLabels.get_Item(i).getNumberFormat() 等於 val）。

**傳回值:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

表示 DataLabels 物件的格式字串。可讀寫 String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 NumberFormat 屬性的預設值。以值設定此屬性時，該值也會設定給 DataLabelCollection 中所有資料標籤的 NumberFormat 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" 會使所有 DataLabels.get_Item(i).getNumberFormat() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示資料標籤的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性表示 DataLabelCollection 中新資料標籤的預設格式。

**傳回值:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

表示資料標籤的位置。可讀寫 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 Position 屬性的預設值。此屬性表示 DataLabel 物件的位置。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 Position 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setPosition(val)" 會使所有 DataLabels.get_Item(i).getPosition() 等於 val）。

**傳回值:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

表示資料標籤的位置。可讀寫 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 Position 屬性的預設值。此屬性表示 DataLabel 物件的位置。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 Position 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setPosition(val)" 會使所有 DataLabels.get_Item(i).getPosition() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

表示指定圖表的資料標籤圖例鍵顯示行為。True 為可見。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLegendKey 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLegendKey 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" 會使所有 DataLabels.get_Item(i).getShowLegendKey() 等於 val）。

**傳回值:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

表示指定圖表的資料標籤圖例鍵顯示行為。True 為可見。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLegendKey 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLegendKey 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" 會使所有 DataLabels.get_Item(i).getShowLegendKey() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

表示指定圖表的資料標籤百分比值顯示行為。True 顯示百分比值。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowValue 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowValue 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" 會使所有 DataLabels.get_Item(i).getShowValue() 等於 val）。

**傳回值:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

表示指定圖表的資料標籤百分比值顯示行為。True 顯示百分比值。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowValue 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowValue 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" 會使所有 DataLabels.get_Item(i).getShowValue() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

表示指定圖表的資料標籤類別名稱顯示行為。True 顯示類別名稱。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowCategoryName 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowCategoryName 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 會使所有 DataLabels.get_Item(i).getShowCategoryName() 等於 val）。

**傳回值:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

表示指定圖表的資料標籤類別名稱顯示行為。True 顯示類別名稱。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowCategoryName 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowCategoryName 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 會使所有 DataLabels.get_Item(i).getShowCategoryName() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

傳回或設定布林值以指示圖表上資料標籤的系列名稱顯示行為。True 顯示系列名稱。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowSeriesName 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowSeriesName 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 會使所有 DataLabels.get_Item(i).getShowSeriesName() 等於 val）。

**傳回值:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

傳回或設定布林值以指示圖表上資料標籤的系列名稱顯示行為。True 顯示系列名稱。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowSeriesName 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowSeriesName 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 會使所有 DataLabels.get_Item(i).getShowSeriesName() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

表示指定圖表的資料標籤百分比值顯示行為。True 顯示百分比值。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowPercentage 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowPercentage 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 會使所有 DataLabels.get_Item(i).getShowPercentage() 等於 val）。

**傳回值:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

表示指定圖表的資料標籤百分比值顯示行為。True 顯示百分比值。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowPercentage 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowPercentage 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 會使所有 DataLabels.get_Item(i).getShowPercentage() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

表示指定圖表的資料標籤氣泡大小值顯示行為。True 顯示氣泡大小值。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowBubbleSize 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowBubbleSize 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 會使所有 DataLabels.get_Item(i).getShowBubbleSize() 等於 val）。

**傳回值:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

表示指定圖表的資料標籤氣泡大小值顯示行為。True 顯示氣泡大小值。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowBubbleSize 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowBubbleSize 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 會使所有 DataLabels.get_Item(i).getShowBubbleSize() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

表示指定圖表的資料標籤引線顯示行為。True 顯示引線。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLeaderLines 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLeaderLines 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 會使所有 DataLabels.get_Item(i).getShowLeaderLines() 等於 val）。

**傳回值:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

表示指定圖表的資料標籤引線顯示行為。True 顯示引線。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLeaderLines 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLeaderLines 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 會使所有 DataLabels.get_Item(i).getShowLeaderLines() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

決定指定圖表的資料標籤將顯示為資料註解或資料標籤。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelAsDataCallout 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelAsDataCallout 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 會使所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等於 val）。

**傳回值:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

決定指定圖表的資料標籤將顯示為資料註解或資料標籤。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelAsDataCallout 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelAsDataCallout 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 會使所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

表示指定圖表的資料標籤儲存格值顯示行為。True 顯示儲存格值。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelValueFromCell 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelValueFromCell 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 會使所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等於 val）。

**傳回值:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

表示指定圖表的資料標籤儲存格值顯示行為。True 顯示儲存格值。False 隱藏。可讀寫布林值。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 ShowLabelValueFromCell 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLabelValueFromCell 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 會使所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

設定或傳回表示圖表上資料標籤使用之分隔符的 Variant。可讀寫 String。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 Separator 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 Separator 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 會使所有 DataLabels.get_Item(i).getSeparator() 等於 val）。

**傳回值:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
``` 
public abstract void setSeparator(String value)
```

設定或傳回表示圖表上資料標籤使用之分隔符的 Variant。可讀寫 String。

--------------------

如果此 DataLabelFormat 物件的父物件是 DataLabelCollection（資料標籤集合），則此屬性取得或設定 DataLabelCollection 中新資料標籤的 Separator 屬性的預設值。以值設定此屬性時，亦會將此值設定給 DataLabelCollection 中所有資料標籤的 Separator 屬性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 會使所有 DataLabels.get_Item(i).getSeparator() 等於 val）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |