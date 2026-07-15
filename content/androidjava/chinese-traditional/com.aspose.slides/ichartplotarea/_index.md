---
title: IChartPlotArea
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示圖表標題屬性。
type: docs
url: /zh-hant/com.aspose.slides/ichartplotarea/
---
**所有已實作的介面：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

表示圖表標題屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFormat()](#getFormat--) | 傳回圖表區域的格式。 |
| [getLayoutTargetType()](#getLayoutTargetType--) | 如果圖表區域的佈局是手動定義的，則此屬性指定是依據內部（不包含 axis 和 axis labels）還是外部（包含 axis 和 axis labels）來佈局圖表區域。 |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | 如果圖表區域的佈局是手動定義的，則此屬性指定是依據內部（不包含 axis 和 axis labels）還是外部（包含 axis 和 axis labels）來佈局圖表區域。 |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


傳回圖表區域的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**回傳：**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


如果圖表區域的佈局是手動定義的，則此屬性指定是依據內部（不包含 axis 和 axis labels）還是外部（包含 axis 和 axis labels）來佈局圖表區域。可讀寫 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))。

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
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**回傳：**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


如果圖表區域的佈局是手動定義的，則此屬性指定是依據內部（不包含 axis 和 axis labels）還是外部（包含 axis 和 axis labels）來佈局圖表區域。可讀寫 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))。

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
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |