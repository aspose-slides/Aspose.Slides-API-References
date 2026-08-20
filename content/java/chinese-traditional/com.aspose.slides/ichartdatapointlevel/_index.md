---
title: IChartDataPointLevel
second_title: Aspose.Slides for Java API Reference
description: 代表資料點層級。
type: docs
url: /zh-hant/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

代表資料點層級。適用於 Treemap 和 Sunburst 圖表。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFormat()](#getFormat--) | 代表資料點層級的格式屬性。 |
| [getLabel()](#getLabel--) | 代表資料點層級的資料標籤。 |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


代表資料點層級的格式屬性。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Treemap, 50, 50, 500, 400);
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      IChartDataPointLevel dataPointLevel = series.getDataPoints().get_Item(7).getDataPointLevels().get_Item(2);
>      dataPointLevel.getFormat().getFill().setFillType(FillType.Solid);
>      dataPointLevel.getFormat().getFill().getSolidFillColor().setColor(Color.Red);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


代表資料點層級的資料標籤。適用於 Treemap 和 Sunburst sereis 類型。唯讀 [IDataLabel](../../com.aspose.slides/idatalabel)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Sunburst, 50, 50, 500, 400);
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      IChartDataPointLevel dataPointLevel = series.getDataPoints().get_Item(0).getDataPointLevels().get_Item(1);
>      dataPointLevel.getLabel().getDataLabelFormat().setShowCategoryName(false);
>      dataPointLevel.getLabel().getDataLabelFormat().setShowValue(true);
>      dataPointLevel.getLabel().getDataLabelFormat().setShowSeriesName(true);
>      dataPointLevel = series.getDataPoints().get_Item(12).getDataPointLevels().get_Item(1);
>      dataPointLevel.getLabel().getTextFormat().getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      dataPointLevel.getLabel().getTextFormat().getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.Red);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)