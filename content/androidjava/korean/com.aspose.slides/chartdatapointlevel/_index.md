---
title: ChartDataPointLevel
second_title: Aspose.Slides for Android용 Java API 참조
description: 데이터 포인트 레벨을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartdatapointlevel/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
```
public class ChartDataPointLevel extends DomObject<ChartDataPointLevelsManager> implements IChartDataPointLevel
```

데이터 포인트 레벨을 나타냅니다. Treemap 및 Sunburst 차트에 적용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) | 데이터 포인트 레벨의 서식 속성을 나타냅니다. |
| [getLabel()](#getLabel--) | 데이터 포인트 레벨의 데이터 레이블을 나타냅니다. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


데이터 포인트 레벨의 서식 속성을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

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


**반환값:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


데이터 포인트 레벨의 데이터 레이블을 나타냅니다. Treemap 및 Sunburst sereis 유형에 적용됩니다. 읽기 전용 [IDataLabel](../../com.aspose.slides/idatalabel).

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

**반환값:**
[IDataLabel](../../com.aspose.slides/idatalabel)