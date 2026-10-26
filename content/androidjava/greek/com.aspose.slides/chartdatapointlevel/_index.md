---
title: ChartDataPointLevel
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει το επίπεδο σημείου δεδομένων.
type: docs
url: /el/com.aspose.slides/chartdatapointlevel/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
```
public class ChartDataPointLevel extends DomObject<ChartDataPointLevelsManager> implements IChartDataPointLevel
```

Αντιπροσωπεύει το επίπεδο σημείου δεδομένων. Εφαρμόζεται σε διάγραμμα Treemap και Sunburst.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τις ιδιότητες μορφοποίησης του επιπέδου σημείου δεδομένων. |
| [getLabel()](#getLabel--) | Αντιπροσωπεύει την ετικέτα δεδομένων του επιπέδου σημείου δεδομένων. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Αντιπροσωπεύει τις ιδιότητες μορφοποίησης του επιπέδου σημείου δεδομένων. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

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

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Αντιπροσωπεύει την ετικέτα δεδομένων του επιπέδου σημείου δεδομένων. Εφαρμόζεται για τύπους σειρών Treemap και Sunburst. Μόνο για ανάγνωση [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Επιστρέφει:**
[IDataLabel](../../com.aspose.slides/idatalabel)