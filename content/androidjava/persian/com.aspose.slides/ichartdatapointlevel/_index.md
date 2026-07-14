---
title: IChartDataPointLevel
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: سطح نقطه داده را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

سطح نقطه داده را نشان می‌دهد. برای نمودارهای Treemap و Sunburst اعمال می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getFormat()](#getFormat--) | خواص فرمت‌بندی سطح نقطه داده را نشان می‌دهد. |
| [getLabel()](#getLabel--) | برچسب داده سطح نقطه داده را نشان می‌دهد. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

خواص فرمت‌بندی سطح نقطه داده را نشان می‌دهد. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

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


**بازمی‌گرداند:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

برچسب داده سطح نقطه داده را نشان می‌دهد. برای انواع سری Treemap و Sunburst اعمال می‌شود. فقط خواندنی [IDataLabel](../../com.aspose.slides/idatalabel).

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


**بازمی‌گرداند:**
[IDataLabel](../../com.aspose.slides/idatalabel)