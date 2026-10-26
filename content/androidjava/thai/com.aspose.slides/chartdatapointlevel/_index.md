---
title: ChartDataPointLevel
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงระดับจุดข้อมูล.
type: docs
url: /th/com.aspose.slides/chartdatapointlevel/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
```
public class ChartDataPointLevel extends DomObject<ChartDataPointLevelsManager> implements IChartDataPointLevel
```

แสดงระดับจุดข้อมูล. ใช้กับแผนภูมิ Treemap และ Sunburst.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFormat()](#getFormat--) | แสดงคุณสมบัติบรรจุรูปแบบของระดับจุดข้อมูล. |
| [getLabel()](#getLabel--) | แสดงป้ายข้อมูลของระดับจุดข้อมูล. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


แสดงคุณสมบัติบรรจุรูปแบบของระดับจุดข้อมูล. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

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
public final IDataLabel getLabel()
```


แสดงป้ายข้อมูลของระดับจุดข้อมูล. ใช้กับประเภทซีรีส์ Treemap และ Sunburst. อ่านอย่างเดียว [IDataLabel](../../com.aspose.slides/idatalabel).

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