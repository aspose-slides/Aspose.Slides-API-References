---
title: IChartTitle
second_title: Aspose.Slides 的 Java API 參考
description: 表示圖表標題屬性。
type: docs
url: /zh-hant/com.aspose.slides/icharttitle/
---
**已實作的介面：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

表示圖表標題屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getOverlay()](#getOverlay--) | 判斷是否允許其他圖表元素覆蓋標題。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 判斷是否允許其他圖表元素覆蓋標題。 |
| [getFormat()](#getFormat--) | 傳回標題的填滿、線條、效果樣式。 |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


判斷是否允許其他圖表元素覆蓋標題。可讀寫布林。

**傳回值：**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


判斷是否允許其他圖表元素覆蓋標題。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


傳回標題的填滿、線條、效果樣式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**傳回值：**
[IFormat](../../com.aspose.slides/iformat)