---
title: IChartPlotArea
second_title: Aspose.Slides for Java API 參考
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
| [getFormat()](#getFormat--) | 傳回繪圖區的格式。 |
| [getLayoutTargetType()](#getLayoutTargetType--) | 如果手動定義繪圖區的佈局，此屬性指定是以內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局繪圖區。 |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | 如果手動定義繪圖區的佈局，此屬性指定是以內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局繪圖區。 |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


**返回：**
傳回繪圖區的格式。 唯讀 [IFormat](../../com.aspose.slides/iformat).

**返回：**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


如果手動定義繪圖區的佈局，此屬性指定是以內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局繪圖區。 讀寫 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**返回：**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


如果手動定義繪圖區的佈局，此屬性指定是以內部（不包括坐標軸和坐標軸標籤）還是外部（包括坐標軸和坐標軸標籤）來佈局繪圖區。 讀寫 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |