---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data point level.
type: docs
url: /vi/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Biểu thị cấp độ điểm dữ liệu. Áp dụng cho biểu đồ Treemap và Sunburst.
## Phương thức

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Biểu thị các thuộc tính định dạng của cấp độ điểm dữ liệu. |
| [getLabel()](#getLabel--) | Biểu thị nhãn dữ liệu của cấp độ điểm dữ liệu. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Biểu thị các thuộc tính định dạng của cấp độ điểm dữ liệu. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

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
public abstract IDataLabel getLabel()
```


Biểu thị nhãn dữ liệu của cấp độ điểm dữ liệu. Áp dụng cho các loại Treemap và Sunburst sereis. Chỉ đọc [IDataLabel](../../com.aspose.slides/idatalabel).

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