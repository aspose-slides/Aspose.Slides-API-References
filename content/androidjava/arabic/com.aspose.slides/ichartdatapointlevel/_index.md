---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data point level.
type: docs
url: /ar/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

يمثل مستوى نقطة البيانات. ينطبق على مخطط Treemap و Sunburst.
## الطرق

| طريقة | وصف |
| --- | --- |
| [getFormat()](#getFormat--) | يمثل خصائص التنسيق لمستوى نقطة البيانات. |
| [getLabel()](#getLabel--) | يمثل تسمية البيانات لمستوى نقطة البيانات. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


يمثل خصائص التنسيق لمستوى نقطة البيانات. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

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

**القيمة المرجعة:**  
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


يمثل تسمية البيانات لمستوى نقطة البيانات. يُطبق على أنواع Treemap و Sunburst sereis. للقراءة فقط [IDataLabel](../../com.aspose.slides/idatalabel).

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

**القيمة المرجعة:**  
[IDataLabel](../../com.aspose.slides/idatalabel)