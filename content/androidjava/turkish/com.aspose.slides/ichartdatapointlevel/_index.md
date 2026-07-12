---
title: IChartDataPointLevel
second_title: Aspose.Slides için Android, Java API Referansı
description: Veri noktası düzeyini temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Veri noktası düzeyini temsil eder. Treemap ve Sunburst grafikleri için uygulanır.
## Yöntemler

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Veri noktası düzeyinin biçimlendirme özelliklerini temsil eder. |
| [getLabel()](#getLabel--) | Veri noktası düzeyinin veri etiketini temsil eder. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Veri noktası düzeyinin biçimlendirme özelliklerini temsil eder. Okunur/yazılır [IFormat](../../com.aspose.slides/iformat).

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

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Veri noktası düzeyinin veri etiketini temsil eder. Treemap ve Sunburst seri türleri için uygulanır. Salt-okunur [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Döndürür:**
[IDataLabel](../../com.aspose.slides/idatalabel)