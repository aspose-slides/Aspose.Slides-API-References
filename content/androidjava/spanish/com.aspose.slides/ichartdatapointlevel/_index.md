---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Representa el nivel del punto de datos.
type: docs
url: /es/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Representa el nivel del punto de datos. Se aplica a los gráficos Treemap y Sunburst.

## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) | Representa las propiedades de formato del nivel del punto de datos. |
| [getLabel()](#getLabel--) | Representa la etiqueta de datos del nivel del punto de datos. |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa las propiedades de formato del nivel del punto de datos. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

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

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Representa la etiqueta de datos del nivel del punto de datos. Aplicado a los tipos de series Treemap y Sunburst. Solo lectura [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Devuelve:**
[IDataLabel](../../com.aspose.slides/idatalabel)