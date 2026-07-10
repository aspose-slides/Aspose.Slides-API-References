---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android Java API 参考
description: 表示数据点级别。
type: docs
url: /zh/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

表示数据点级别。适用于 Treemap 和 Sunburst 图表。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) | 表示数据点级别的格式属性。 |
| [getLabel()](#getLabel--) | 表示数据点级别的数据标签。 |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示数据点级别的格式属性。读/写 [IFormat](../../com.aspose.slides/iformat)。

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

表示数据点级别的数据标签。适用于 Treemap 和 Sunburst 系列类型。只读 [IDataLabel](../../com.aspose.slides/idatalabel)。


Presentation pres = new Presentation();
 try
 {
     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Sunburst, 50, 50, 500, 400);
     IChartSeries series = chart.getChartData().getSeries().get_Item(0);
     IChartDataPointLevel dataPointLevel = series.getDataPoints().get_Item(0).getDataPointLevels().get_Item(1);
     dataPointLevel.getLabel().getDataLabelFormat().setShowCategoryName(false);
     dataPointLevel.getLabel().getDataLabelFormat().setShowValue(true);
     dataPointLevel.getLabel().getDataLabelFormat().setShowSeriesName(true);
     dataPointLevel = series.getDataPoints().get_Item(12).getDataPointLevels().get_Item(1);
     dataPointLevel.getLabel().getTextFormat().getPortionFormat().getFillFormat().setFillType(FillType.Solid);
     dataPointLevel.getLabel().getTextFormat().getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.Red);
 } finally {
     if (pres != null) pres.dispose();
 }

**返回:**  
[IDataLabel](../../com.aspose.slides/idatalabel)