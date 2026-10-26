---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Représente le niveau du point de données.
type: docs
url: /fr/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Représente le niveau du point de données. S'applique aux graphiques Treemap et Sunburst.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Représente les propriétés de formatage du niveau du point de données. |
| [getLabel()](#getLabel--) | Représente l'étiquette de données du niveau du point de données. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Représente les propriétés de formatage du niveau du point de données. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

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
**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()


Représente l'étiquette de données du niveau du point de données. Appliqué aux types de séries Treemap et Sunburst. Lecture seule [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Renvoie:**  
[IDataLabel](../../com.aspose.slides/idatalabel)