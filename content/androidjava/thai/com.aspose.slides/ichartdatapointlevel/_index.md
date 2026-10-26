---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data point level.
type: docs
url: /th/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

เป็นตัวแทนของระดับข้อมูลจุด. ใช้กับแผนภูมิ Treemap และ Sunburst

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFormat()](#getFormat--) | เป็นตัวแทนของคุณสมบัติการจัดรูปแบบของระดับข้อมูลจุด. |
| [getLabel()](#getLabel--) | เป็นตัวแทนของป้ายข้อมูลของระดับข้อมูลจุด. |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

เป็นตัวแทนของคุณสมบัติการจัดรูปแบบของระดับข้อมูลจุด. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

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

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

เป็นตัวแทนของป้ายข้อมูลของระดับข้อมูลจุด. ใช้กับประเภทแผนภูมิ Treemap และ Sunburst series. อ่านอย่างเดียว [IDataLabel](../../com.aspose.slides/idatalabel).

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

**คืนค่า:**
[IDataLabel](../../com.aspose.slides/idatalabel)