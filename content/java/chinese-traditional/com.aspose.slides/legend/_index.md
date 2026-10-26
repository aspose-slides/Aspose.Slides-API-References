---
title: Legend
second_title: Aspose.Slides for Java API 參考
description: 代表圖表圖例屬性。
type: docs
url: /zh-hant/com.aspose.slides/legend/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**  
[com.aspose.slides.ILegend](../../com.aspose.slides/ilegend)  
```
public class Legend extends DomObject<Chart> implements ILegend
```

表示圖表的圖例屬性。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getX()](#getX--) | 傳回或設定圖例的 x 座標，以圖表寬度的比例表示。 |
| [setX(float value)](#setX-float-) | 傳回或設定圖例的 x 座標，以圖表寬度的比例表示。 |
| [getY()](#getY--) | 傳回或設定圖例的 y 座標，以圖表高度的比例表示。 |
| [setY(float value)](#setY-float-) | 傳回或設定圖例的 y 座標，以圖表高度的比例表示。 |
| [getWidth()](#getWidth--) | 傳回或設定圖例的寬度，以圖表寬度的比例表示。 |
| [setWidth(float value)](#setWidth-float-) | 傳回或設定圖例的寬度，以圖表寬度的比例表示。 |
| [getHeight()](#getHeight--) | 傳回或設定圖例的高度，以圖表高度的比例表示。 |
| [setHeight(float value)](#setHeight-float-) | 傳回或設定圖例的高度，以圖表高度的比例表示。 |
| [getRight()](#getRight--) | 右側。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getOverlay()](#getOverlay--) | 判斷是否允許其他圖表元素覆蓋圖例。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 判斷是否允許其他圖表元素覆蓋圖例。 |
| [getTextFormat()](#getTextFormat--) | 文字格式。 |
| [getPosition()](#getPosition--) | 指定圖例在圖表上的位置。 |
| [setPosition(int value)](#setPosition-int-) | 指定圖例在圖表上的位置。 |
| [getFormat()](#getFormat--) | 傳回圖例的格式。 |
| [getChart()](#getChart--) | 傳回圖表。 |
| [getEntries()](#getEntries--) | 取得圖例項目。 |
| [getActualX()](#getActualX--) | 指定圖表元素相對於圖表左上角的實際 x 位置（左）。 |
| [getActualY()](#getActualY--) | 指定圖表元素相對於圖表左上角的實際上緣位置。 |
| [getActualWidth()](#getActualWidth--) | 指定圖表元素的實際寬度。 |
| [getActualHeight()](#getActualHeight--) | 指定圖表元素的實際高度。 |
| [getSlide()](#getSlide--) | 傳回 FillFormat 所屬的投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 FillFormat 所屬的簡報。 |

### getX() {#getX--}
```
public final float getX()
```

傳回或設定圖例的 x 座標，以圖表寬度的比例表示。可讀寫 float。

**回傳值:**  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

傳回或設定圖例的 x 座標，以圖表寬度的比例表示。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

傳回或設定圖例的 y 座標，以圖表高度的比例表示。可讀寫 float。

**回傳值:**  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

傳回或設定圖例的 y 座標，以圖表高度的比例表示。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

傳回或設定圖例的寬度，以圖表寬度的比例表示。可讀寫 float。

**回傳值:**  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

傳回或設定圖例的寬度，以圖表寬度的比例表示。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

傳回或設定圖例的高度，以圖表高度的比例表示。可讀寫 float。

**回傳值:**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

傳回或設定圖例的高度，以圖表高度的比例表示。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右側。唯讀 float。

**回傳值:**  
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

底部。唯讀 float。

**回傳值:**  
float

### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```

判斷是否允許其他圖表元素覆蓋圖例。可讀寫 boolean。

**回傳值:**  
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```

判斷是否允許其他圖表元素覆蓋圖例。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

文字格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**回傳值:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

指定圖例在圖表上的位置。X、Y、Width、Height 屬性的非 NaN 值會覆寫此屬性的效果。可讀寫 [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**回傳值:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

指定圖例在圖表上的位置。X、Y、Width、Height 屬性的非 NaN 值會覆寫此屬性的效果。可讀寫 [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

傳回圖例的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**回傳值:**  
[IFormat](../../com.aspose.slides/iformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

傳回圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**回傳值:**  
[IChart](../../com.aspose.slides/ichart)

### getEntries() {#getEntries--}
```
public final ILegendEntryCollection getEntries()
```

取得圖例項目。唯讀 [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)。

**回傳值:**  
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定圖表元素相對於圖表左上角的實際 x 位置（左）。在呼叫 IChart.validateChartLayout() 後可取得實際值。唯讀 float。

**回傳值:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定圖表元素相對於圖表左上角的實際上緣位置。在呼叫 IChart.validateChartLayout() 後可取得實際值。唯讀 float。

**回傳值:**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定圖表元素的實際寬度。在呼叫 IChart.validateChartLayout() 後可取得實際值。唯讀 float。

**回傳值:**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定圖表元素的實際高度。在呼叫 IChart.validateChartLayout() 後可取得實際值。唯讀 float。

**回傳值:**  
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回 FillFormat 所屬的投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**回傳值:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回 FillFormat 所屬的簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**回傳值:**  
[IPresentation](../../com.aspose.slides/ipresentation)