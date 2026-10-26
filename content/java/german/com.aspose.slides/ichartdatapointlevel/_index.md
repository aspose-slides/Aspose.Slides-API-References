---
title: IChartDataPointLevel
second_title: Aspose.Slides for Java API Reference
description: Stellt die Datenpunktenebene dar.
type: docs
url: /de/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Stellt die Datenpunktenebene dar. Gilt für Treemap- und Sunburst-Diagramme.
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Stellt die Formatierungseigenschaften der Datenpunktenebene dar. |
| [getLabel()](#getLabel--) | Stellt die Datenbeschriftung der Datenpunktenebene dar. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt die Formatierungseigenschaften der Datenpunktenebene dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

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


**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Stellt die Datenbeschriftung der Datenpunktenebene dar. Angewendet für Treemap- und Sunburst-Serientypen. Nur lesbar [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Rückgabe:**
[IDataLabel](../../com.aspose.slides/idatalabel)