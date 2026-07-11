---
title: ChartDataPointLevel
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет уровень точки данных.
type: docs
url: /ru/com.aspose.slides/chartdatapointlevel/
---
**Наследование:**  
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**  
[com.aspose.slides.IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)  
```
public class ChartDataPointLevel extends DomObject<ChartDataPointLevelsManager> implements IChartDataPointLevel
```

Представляет уровень точек данных. Применяется для диаграмм Treemap и Sunburst.

## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) | Представляет свойства форматирования уровня точек данных. |
| [getLabel()](#getLabel--) | Представляет подпись данных уровня точек данных. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Представляет свойства форматирования уровня точек данных. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

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

**Возвращает:**  
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Представляет подпись данных уровня точек данных. Применяется для типов серий Treemap и Sunburst. Только для чтения [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Возвращает:**  
[IDataLabel](../../com.aspose.slides/idatalabel)