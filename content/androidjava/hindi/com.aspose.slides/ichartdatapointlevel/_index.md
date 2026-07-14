---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data point level.
type: docs
url: /hi/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

डेटा पॉइंट स्तर का प्रतिनिधित्व करता है। Treemap और Sunburst चार्ट के लिए लागू होता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) | डेटा पॉइंट स्तर की फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। |
| [getLabel()](#getLabel--) | डेटा पॉइंट स्तर का डेटा लेबल दर्शाता है। |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


डेटा पॉइंट स्तर की फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat)।

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

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


डेटा पॉइंट स्तर का डेटा लेबल दर्शाता है। Treemap और Sunburst सीरीज़ प्रकारों के लिए लागू किया जाता है। केवल-पठन [IDataLabel](../../com.aspose.slides/idatalabel)।

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


**रिटर्न:**
[IDataLabel](../../com.aspose.slides/idatalabel)