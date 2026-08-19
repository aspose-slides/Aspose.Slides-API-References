---
title: IChartDataPointLevel
second_title: Aspose.Slides for Java API Reference
description: Represents data point level.
type: docs
url: /id/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Mewakili tingkat titik data. Berlaku untuk diagram Treemap dan Sunburst.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat()](#getFormat--) | Represents formatting properties of data point level. |
| [getLabel()](#getLabel--) | Represents data label of data point level. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Mewakili properti format tingkat titik data. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

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

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Mewakili label data tingkat titik data. Diterapkan untuk tipe seri Treemap dan Sunburst. Baca-saja [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Mengembalikan:**
[IDataLabel](../../com.aspose.slides/idatalabel)