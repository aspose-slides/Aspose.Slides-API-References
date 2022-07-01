---
title: getLayoutTargetType
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 90
url: /php-java/chartplotarea/getlayouttargettype/
---

## getLayoutTargetType()  method

  If layout of the plot area defined manually this property specifies whether 
  to layout the plot area by its inside (not including axis and axis labels) or outside
  (including axis and axis labels).
  Read/write  LayoutTargetType( #getLayoutTargetType/ #setLayoutTargetType(int)).
  
  Presentation presentation = new Presentation();
  try
  {
      ISlide slide = presentation.getSlides().get_Item(0);
      IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
      chart.getPlotArea().setX(0.2f);
      chart.getPlotArea().setY(0.2f);
      chart.getPlotArea().setWidth(0.7f);
      chart.getPlotArea().setHeight(0.7f);
      chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
      ...
  } finally {
      if (presentation != null) presentation.dispose();
  }
  

```php
  $presentation = new Presentation();
  try {
    $slide = $presentation->getSlides()->get_Item(0);
    $chart = $slide->getShapes()->addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
    $chart->getPlotArea()->setX(0.2);
    $chart->getPlotArea()->setY(0.2);
    $chart->getPlotArea()->setWidth(0.7);
    $chart->getPlotArea()->setHeight(0.7);
    $chart->getPlotArea()->setLayoutTargetType(LayoutTargetType.Inner);
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

### Returns
#setLayoutTargetType(int)


---


