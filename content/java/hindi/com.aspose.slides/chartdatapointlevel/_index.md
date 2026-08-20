---
title: ChartDataPointLevel
second_title: Aspose.Slides for Java API संदर्भ
description: डेटा पॉइंट स्तर का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartdatapointlevel/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
```
public class ChartDataPointLevel extends DomObject<ChartDataPointLevelsManager> implements IChartDataPointLevel
```

डेटा पॉइंट स्तर का प्रतिनिधित्व करता है। Treemap और Sunburst चार्ट के लिए लागू होता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) | डेटा पॉइंट स्तर के फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। |
| [getLabel()](#getLabel--) | डेटा पॉइंट स्तर का डेटा लेबल प्रतिनिधित्व करता है। |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


डेटा पॉइंट स्तर के फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat)।

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

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


डेटा पॉइंट स्तर का डेटा लेबल प्रतिनिधित्व करता है। Treemap और Sunburst सीरीज़ प्रकारों के लिए लागू। केवल-पढ़ने योग्य [IDataLabel](../../com.aspose.slides/idatalabel)।

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

**वापसी:**
[IDataLabel](../../com.aspose.slides/idatalabel)