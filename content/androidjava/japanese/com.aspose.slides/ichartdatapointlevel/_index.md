---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: データポイントレベルを表します。
type: docs
url: /ja/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

データポイントレベルを表します。Treemap と Sunburst チャートに適用されます。
## メソッド

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | データポイントレベルの書式設定プロパティを表します。 |
| [getLabel()](#getLabel--) | データポイントレベルのデータラベルを表します。 |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

データポイントレベルの書式設定プロパティを表します。読み取り/書き込み [IFormat](../../com.aspose.slides/iformat)。

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


**返り値:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

データポイントレベルのデータラベルを表します。Treemap と Sunburst 系列タイプに適用されます。読み取り専用 [IDataLabel](../../com.aspose.slides/idatalabel)。

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


**返り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)