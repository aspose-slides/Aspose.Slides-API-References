---
title: getMasterTheme
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 240
url: /php-java/presentation/getmastertheme/
---

## getMasterTheme()  method

 Returns master theme.
 Read-only  IMasterTheme.
 

 The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
 
```php
  // Instantiate a presentation object that represents a presentation file
  $pres = new Presentation("Subtle_Moderate_Intense.pptx");
  try {
    $pres->getMasterTheme()->getFormatScheme()->getLineStyles()->get_Item(0)->getFillFormat()->getSolidFillColor()->setColor(Color::RED);
    $pres->getMasterTheme()->getFormatScheme()->getLineStyles()->get_Item(2)->setFillType(FillType.Solid);
    $pres->getMasterTheme()->getFormatScheme()->getLineStyles()->get_Item(2)->getSolidFillColor()->setColor(Color::GREEN);
    $pres->getMasterTheme()->getFormatScheme()->getLineStyles()->get_Item(2)->getEffectFormat()->getOuterShadowEffect()->setDistance(10.0);
    $pres->save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[MasterTheme](../../mastertheme)


---


