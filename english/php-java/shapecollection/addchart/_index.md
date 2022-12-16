---
title: addChart
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 70
url: /php-java/shapecollection/addchart/
---

## addChart(int type, float x, float y, float width, float height)  method

 Creates a new Chart, initialize it with sample series data and settings and adds 
 it to the end of the collection.
 

 The following example shows how to create Chart in PowerPoint Presentation.
 
```php
  // Instantiates the Presentation class that represents a PPTX file
  $pres = new Presentation();
  try {
    // Accesses the first slide
    $sld = $pres->getSlides()->get_Item(0);
    // Adds a chart with its default data
    $chart = $sld->getShapes()->addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
    // Sets the chart title
    $chart->getChartTitle()->addTextFrameForOverriding("Sample Title");
    $chart->getChartTitle()->getTextFrameForOverriding()->getTextFrameFormat()->setCenterText(NullableBool.True);
    $chart->getChartTitle()->setHeight(20);
    $chart->setTitle(true);
    // Sets the first series to show values
    $chart->getChartData()->getSeries()->get_Item(0)->getLabels()->getDefaultDataLabelFormat()->setShowValue(true);
    // Sets the index for the chart data sheet
    $defaultWorksheetIndex = 0;
    // Gets the chart data worksheet
    $fact = $chart->getChartData()->getChartDataWorkbook();
    // Deletes the default generated series and categories
    $chart->getChartData()->getSeries()->clear();
    $chart->getChartData()->getCategories()->clear();
    // Adds new series
    $chart->getChartData()->getSeries()->add($fact->getCell($defaultWorksheetIndex, 0, 1, "Series 1"), $chart->getType());
    $chart->getChartData()->getSeries()->add($fact->getCell($defaultWorksheetIndex, 0, 2, "Series 2"), $chart->getType());
    // Adds new categories
    $chart->getChartData()->getCategories()->add($fact->getCell($defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
    $chart->getChartData()->getCategories()->add($fact->getCell($defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
    $chart->getChartData()->getCategories()->add($fact->getCell($defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
    // Takes the first chart series
    $series = $chart->getChartData()->getSeries()->get_Item(0);
    // Populates series data
    $series->getDataPoints()->addDataPointForBarSeries($fact->getCell($defaultWorksheetIndex, 1, 1, 20));
    $series->getDataPoints()->addDataPointForBarSeries($fact->getCell($defaultWorksheetIndex, 2, 1, 50));
    $series->getDataPoints()->addDataPointForBarSeries($fact->getCell($defaultWorksheetIndex, 3, 1, 30));
    // Sets the fill color for the series
    $series->getFormat()->getFill()->setFillType(FillType.Solid);
    $series->getFormat()->getFill()->getSolidFillColor()->setColor(Color::RED);
    // Takes the second chart series
    $series = $chart->getChartData()->getSeries()->get_Item(1);
    // Populates series data
    $series->getDataPoints()->addDataPointForBarSeries($fact->getCell($defaultWorksheetIndex, 1, 2, 30));
    $series->getDataPoints()->addDataPointForBarSeries($fact->getCell($defaultWorksheetIndex, 2, 2, 10));
    $series->getDataPoints()->addDataPointForBarSeries($fact->getCell($defaultWorksheetIndex, 3, 2, 60));
    // Sets the fill color for series
    $series->getFormat()->getFill()->setFillType(FillType.Solid);
    $series->getFormat()->getFill()->getSolidFillColor()->setColor(Color::GREEN);
    // Sets the first label to show Category name
    $lbl = $series->getDataPoints()->get_Item(0)->getLabel();
    $lbl->getDataLabelFormat()->setShowCategoryName(true);
    $lbl = $series->getDataPoints()->get_Item(1)->getLabel();
    $lbl->getDataLabelFormat()->setShowSeriesName(true);
    // Sets the series to show the value for the third label
    $lbl = $series->getDataPoints()->get_Item(2)->getLabel();
    $lbl->getDataLabelFormat()->setShowValue(true);
    $lbl->getDataLabelFormat()->setShowSeriesName(true);
    $lbl->getDataLabelFormat()->setSeparator("/");
    // Saves the PPTX file to disk
    $pres->save("AsposeChart_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |

### Returns
[Chart](../../chart)


---


## addChart(int type, float x, float y, float width, float height, boolean initWithSample)  method

 Creates a new Chart and adds it to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of chart. |
| x | float | X coordinate of a new chart. |
| y | float | Y coordinate of a new chart. |
| width | float | Chart's width. |
| height | float | Chart's height. |
| initWithSample | boolean | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

### Returns
[Chart](../../chart)


---


