---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Představuje úroveň datového bodu.
type: docs
url: /cs/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Představuje úroveň datového bodu. Použitelné pro grafy Treemap a Sunburst.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFormat()](#getFormat--) | Představuje vlastnosti formátování úrovně datového bodu. |
| [getLabel()](#getLabel--) | Představuje popisek datové úrovně bodu. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Představuje vlastnosti formátování úrovně datového bodu. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

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

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Představuje popisek datové úrovně bodu. Použito pro typy řad Treemap a Sunburst. Pouze pro čtení [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)