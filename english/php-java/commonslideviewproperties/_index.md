---
title: CommonSlideViewProperties
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/commonslideviewproperties/
---

## CommonSlideViewProperties class

 Represents common slide view properties.
 

 The following example shows how to set the zoom value for slide of PowerPoint Presentation.
 
```php
  // Instantiate a Presentation object that represents a presentation file
  $pres = new Presentation("demo.pptx");
  try {
    // Setting View Properties of Presentation
    $pres->getViewProperties()->getSlideViewProperties()->setScale(100);// Zoom value in percentages for slide view

    $pres->getViewProperties()->getNotesViewProperties()->setScale(100);// Zoom value in percentages for notes view

    $pres->save("Zoom_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Methods

| Name | Description |
| --- | --- |
| [getScale](getscale)() | Specifies the view scaling ratio in percentages. Read/write int. |
| [getVariableScale](getvariablescale)() | Specifies that the view content should automatically scale to best fit the current window size. Read/write boolean. |
| [setScale](setscale)(int) | Specifies the view scaling ratio in percentages. Read/write int. |
| [setVariableScale](setvariablescale)(boolean) | Specifies that the view content should automatically scale to best fit the current window size. Read/write boolean. |
