---
title: IChartDataPointLevel
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar datapunktsnivå.
type: docs
url: /sv/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Representerar datapunktsnivå. Gäller för Treemap- och Sunburst-diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) | Representerar formateringsegenskaper för datapunktsnivå. |
| [getLabel()](#getLabel--) | Representerar datamärkning för datapunktsnivå. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Representerar formateringsegenskaper för datapunktsnivå. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

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


**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Representerar datamärkning för datapunktsnivå. Tillämpas för Treemap- och Sunburst-serietyper. Skrivskyddad [IDataLabel](../../com.aspose.slides/idatalabel).

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


**Returnerar:**
[IDataLabel](../../com.aspose.slides/idatalabel)