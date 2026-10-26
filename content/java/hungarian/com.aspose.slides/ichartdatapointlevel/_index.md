---
title: IChartDataPointLevel
second_title: Aspose.Slides for Java API Reference
description: Képviseli az adatpont szintet.
type: docs
url: /hu/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Képviseli az adatpont szintet. Alkalmazható a Treemap és a Sunburst diagramra.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFormat()](#getFormat--) | Képviseli az adatpont szint formázási tulajdonságait. |
| [getLabel()](#getLabel--) | Képviseli az adatpont szint adatcímkéjét. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Képviseli az adatpont szint formázási tulajdonságait. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

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


**Visszatér:**  
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Képviseli az adatpont szint adatcímkéjét. Alkalmazva a Treemap és a Sunburst sereis típusokhoz. Csak olvasás [IDataLabel](../../com.aspose.slides/idatalabel).

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


**Visszatér:**  
[IDataLabel](../../com.aspose.slides/idatalabel)