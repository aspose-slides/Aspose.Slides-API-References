---
title: IChartDataPointLevel
second_title: Aspose.Slides for Java API Reference
description: نمایانگر سطح نقطه داده.
type: docs
url: /fa/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

نمایانگر سطح نقطه داده. برای نمودارهای Treemap و Sunburst اعمال می‌شود.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getFormat()](#getFormat--) | نمایانگر ویژگی‌های قالب‌بندی سطح نقطه داده. |
| [getLabel()](#getLabel--) | نمایانگر برچسب داده سطح نقطه داده. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


نمایانگر ویژگی‌های قالب‌بندی سطح نقطه داده. قابل‌خواندن/قابل‌نوشتن [IFormat](../../com.aspose.slides/iformat).

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

**باز می‌گرداند:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


نمایانگر برچسب داده سطح نقطه داده. برای انواع سری‌های Treemap و Sunburst اعمال می‌شود. فقط خواندنی [IDataLabel](../../com.aspose.slides/idatalabel).

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

**باز می‌گرداند:**
[IDataLabel](../../com.aspose.slides/idatalabel)