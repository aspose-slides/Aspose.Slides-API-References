---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data point level.
type: docs
url: /it/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Rappresenta il livello del punto dati. Si applica a grafici Treemap e Sunburst.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) | Rappresenta le proprietà di formattazione del livello del punto dati. |
| [getLabel()](#getLabel--) | Rappresenta l'etichetta dati del livello del punto dati. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Rappresenta le proprietà di formattazione del livello del punto dati. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

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

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Rappresenta l'etichetta dati del livello del punto dati. Applicato per tipi di serie Treemap e Sunburst. Solo lettura [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Restituisce:**
[IDataLabel](../../com.aspose.slides/idatalabel)