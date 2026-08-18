---
title: IChartDataPointLevel
second_title: Aspose.Slides for Java API Reference
description: データポイント レベルを表します。
type: docs
url: /ja/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

データポイント レベルを表します。Treemap および Sunburst チャートに適用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFormat()](#getFormat--) | データポイント レベルの書式設定プロパティを表します。 |
| [getLabel()](#getLabel--) | データポイント レベルのデータ ラベルを表します。 |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

データポイント レベルの書式設定プロパティを表します。読み取り/書き込み [IFormat](../../com.aspose.slides/iformat).

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

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

データポイント レベルのデータ ラベルを表します。Treemap および Sunburst シリーズタイプに適用されます。読み取り専用 [IDataLabel](../../com.aspose.slides/idatalabel)。

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

**戻り値:**
[IDataLabel](../../com.aspose.slides/idatalabel)