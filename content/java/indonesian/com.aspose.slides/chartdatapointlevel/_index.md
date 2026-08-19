---
title: ChartDataPointLevel
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili tingkat titik data.
type: docs
url: /id/com.aspose.slides/chartdatapointlevel/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
```
public class ChartDataPointLevel extends DomObject<ChartDataPointLevelsManager> implements IChartDataPointLevel
```

Mewakili tingkat titik data. Berlaku untuk diagram Treemap dan Sunburst.
## Metode

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Mewakili properti pemformatan tingkat titik data. |
| [getLabel()](#getLabel--) | Mewakili label data tingkat titik data. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Mewakili properti pemformatan tingkat titik data. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

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
public final IDataLabel getLabel()
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