---
title: ChartPlotArea
second_title: Aspose.Slides for Java API 參考
description: 表示圖表應該繪製的矩形。
type: docs
url: /zh-hant/com.aspose.slides/chartplotarea/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

表示應繪製圖表的矩形。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFormat()](#getFormat--) | 傳回繪圖區域的格式。 |
| [getX()](#getX--) | 傳回或設定繪圖區域邊界框左上角的 x 座標，以圖表寬度的比例表示（從 0 到 1）。 |
| [setX(float value)](#setX-float-) | 傳回或設定繪圖區域邊界框左上角的 x 座標，以圖表寬度的比例表示（從 0 到 1）。 |
| [getY()](#getY--) | 傳回或設定繪圖區域邊界框左上角的 y 座標，以圖表高度的比例表示（從 0 到 1）。 |
| [setY(float value)](#setY-float-) | 傳回或設定繪圖區域邊界框左上角的 y 座標，以圖表高度的比例表示（從 0 到 1）。 |
| [getWidth()](#getWidth--) | 傳回或設定繪圖區域邊界框的寬度，以圖表寬度的比例表示（從 0 到 1）。 |
| [setWidth(float value)](#setWidth-float-) | 傳回或設定繪圖區域邊界框的寬度，以圖表寬度的比例表示（從 0 到 1）。 |
| [getHeight()](#getHeight--) | 傳回或設定繪圖區域邊界框的高度，以圖表高度的比例表示（從 0 到 1）。 |
| [setHeight(float value)](#setHeight-float-) | 傳回或設定繪圖區域邊界框的高度，以圖表高度的比例表示（從 0 到 1）。 |
| [getRight()](#getRight--) | 右側。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getChart()](#getChart--) | 圖表。 |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | 定義位置的計算方式：true \u2013 自動計算；由 X、Y、Width、Height 屬性定義。 |
| [getLayoutTargetType()](#getLayoutTargetType--) | 如果手動定義繪圖區域的佈局，此屬性指定是以內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局繪圖區域。 |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | 如果手動定義繪圖區域的佈局，此屬性指定是以內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局繪圖區域。 |
| [getActualX()](#getActualX--) | 指定圖表元素相對於圖表左上角的實際 x 位置（左）。 |
| [getActualY()](#getActualY--) | 指定圖表元素相對於圖表左上角的實際上緣位置。 |
| [getActualWidth()](#getActualWidth--) | 指定圖表元素的實際寬度。 |
| [getActualHeight()](#getActualHeight--) | 指定圖表元素的實際高度。 |
| [getSlide()](#getSlide--) | 傳回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 FillFormat 的父簡報。 |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

傳回繪圖區域的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**傳回：**
[IFormat](../../com.aspose.slides/iformat)

### getX() {#getX--}
```
public final float getX()
```

傳回或設定繪圖區域邊界框左上角的 x 座標，以圖表寬度的比例表示（從 0 到 1）。可讀寫 float。

**傳回：**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

傳回或設定繪圖區域邊界框左上角的 x 座標，以圖表寬度的比例表示（從 0 到 1）。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

傳回或設定繪圖區域邊界框左上角的 y 座標，以圖表高度的比例表示（從 0 到 1）。可讀寫 float。

**傳回：**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

傳回或設定繪圖區域邊界框左上角的 y 座標，以圖表高度的比例表示（從 0 到 1）。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

傳回或設定繪圖區域邊界框的寬度，以圖表寬度的比例表示（從 0 到 1）。可讀寫 float。

**傳回：**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

傳回或設定繪圖區域邊界框的寬度，以圖表寬度的比例表示（從 0 到 1）。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

傳回或設定繪圖區域邊界框的高度，以圖表高度的比例表示（從 0 到 1）。可讀寫 float。

**傳回：**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

傳回或設定繪圖區域邊界框的高度，以圖表高度的比例表示（從 0 到 1）。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右側。唯讀 float。

**傳回：**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

底部。唯讀 float。

**傳回：**
float

### getChart() {#getChart--}
```
public final IChart getChart()
```

圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**傳回：**
[IChart](../../com.aspose.slides/ichart)

### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

定義位置的計算方式：true \u2013 自動計算；由 X、Y、Width、Height 屬性定義。唯讀 boolean。

**傳回：**
boolean

### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

如果手動定義繪圖區域的佈局，此屬性指定是以內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局繪圖區域。可讀寫 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))。

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**傳回：**
int

### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

如果手動定義繪圖區域的佈局，此屬性指定是以內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局繪圖區域。可讀寫 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))。

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定圖表元素相對於圖表左上角的實際 x 位置（左）。在取得實際值之前，請先呼叫 IChart.ValidateChartLayout() 方法。唯讀 float。

**傳回：**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定圖表元素相對於圖表左上角的實際上緣位置。在取得實際值之前，請先呼叫 IChart.ValidateChartLayout() 方法。唯讀 float。

**傳回：**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定圖表元素的實際寬度。在取得實際值之前，請先呼叫 IChart.ValidateChartLayout() 方法。唯讀 float。

**傳回：**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定圖表元素的實際高度。在取得實際值之前，請先呼叫 IChart.ValidateChartLayout() 方法。唯讀 float。

**傳回：**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回：**
[IPresentation](../../com.aspose.slides/ipresentation)