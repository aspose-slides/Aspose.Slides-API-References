---
title: IChartDataPointLevel
second_title: Aspose.Slides for Android μέσω αναφοράς Java API
description: Αναπαριστά το επίπεδο σημείου δεδομένων.
type: docs
url: /el/com.aspose.slides/ichartdatapointlevel/
---```
public interface IChartDataPointLevel
```

Αναπαριστά το επίπεδο σημείου δεδομένων. Ισχύει για διαγράμματα Treemap και Sunburst.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) | Αναπαριστά τις ιδιότητες μορφοποίησης του επιπέδου σημείου δεδομένων. |
| [getLabel()](#getLabel--) | Αναπαριστά την ετικέτα δεδομένων του επιπέδου σημείου δεδομένων. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Αναπαριστά τις ιδιότητες μορφοποίησης του επιπέδου σημείου δεδομένων. Ανάγνωση/Εγγραφή [IFormat](../../com.aspose.slides/iformat).

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
public abstract IDataLabel getLabel()
```

Αναπαριστά την ετικέτα δεδομένων του επιπέδου σημείου δεδομένων. Εφαρμόζεται για τύπους σειρών Treemap και Sunburst. Μόνο για ανάγνωση [IDataLabel](../../com.aspose.slides/idatalabel).

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