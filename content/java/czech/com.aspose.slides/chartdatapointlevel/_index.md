---
title: ChartDataPointLevel
second_title: Aspose.Slides pro Java API referenční příručka
description: Reprezentuje úroveň datového bodu.
type: docs
url: /cs/com.aspose.slides/chartdatapointlevel/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
```
public class ChartDataPointLevel extends DomObject<ChartDataPointLevelsManager> implements IChartDataPointLevel
```

Reprezentuje úroveň datového bodu. Používá se pro grafy Treemap a Sunburst.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFormat()](#getFormat--) | Reprezentuje formátovací vlastnosti úrovně datového bodu. |
| [getLabel()](#getLabel--) | Reprezentuje popisek úrovně datového bodu. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Reprezentuje formátovací vlastnosti úrovně datového bodu. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

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
public final IDataLabel getLabel()
```


Reprezentuje popisek úrovně datového bodu. Používá se pro typy řad Treemap a Sunburst. Pouze ke čtení [IDataLabel](../../com.aspose.slides/idatalabel).

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