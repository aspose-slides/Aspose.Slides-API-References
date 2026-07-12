---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Representa o nível de ponto de dados.
type: docs
url: /pt/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Representa o nível de ponto de dados. Aplica-se a gráficos Treemap e Sunburst.

## Métodos

| Método | Descrição |
| --- | --- |
| [getFormat()](#getFormat--) | Represents formatting properties of data point level. |
| [getLabel()](#getLabel--) | Represents data label of data point level. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa as propriedades de formatação do nível de ponto de dados. Leitura/gravação [IFormat](../../com.aspose.slides/iformat).

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

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Representa o rótulo de dados do nível de ponto de dados. Aplicado para os tipos de série Treemap e Sunburst. Somente leitura [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Retorna:**
[IDataLabel](../../com.aspose.slides/idatalabel)