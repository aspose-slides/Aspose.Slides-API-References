---
title: ChartDataPointLevel
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn cấp độ điểm dữ liệu.
type: docs
url: /vi/com.aspose.slides/chartdatapointlevel/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả giao diện đã triển khai:**
[com.aspose.slides.IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
```
public class ChartDataPointLevel extends DomObject<ChartDataPointLevelsManager> implements IChartDataPointLevel
```

Biểu diễn cấp độ điểm dữ liệu. Áp dụng cho biểu đồ Treemap và Sunburst.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFormat()](#getFormat--) | Biểu diễn các thuộc tính định dạng của cấp độ điểm dữ liệu. |
| [getLabel()](#getLabel--) | Biểu diễn nhãn dữ liệu của cấp độ điểm dữ liệu. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Biểu diễn các thuộc tính định dạng của cấp độ điểm dữ liệu. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

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

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Biểu diễn nhãn dữ liệu của cấp độ điểm dữ liệu. Được áp dụng cho các loại sê-ri Treemap và Sunburst. Chỉ đọc [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Trả về:**
[IDataLabel](../../com.aspose.slides/idatalabel)