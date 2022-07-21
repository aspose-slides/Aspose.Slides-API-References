---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 150
url: /php-java/threedformat/geteffective/
---

## getEffective()  method

 Gets effective 3-D formatting data with the inheritance applied.
 

 This example demonstrates how to get effective properties for camera, light rig and shape's top bevel.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $threeDEffectiveData = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0)->getThreeDFormat()->getEffective();
    echo("= Effective camera properties =");
    echo("Type: " + $threeDEffectiveData->getCamera()->getCameraType());
    echo("Field of view: " + $threeDEffectiveData->getCamera()->getFieldOfViewAngle());
    echo("Zoom: " + $threeDEffectiveData->getCamera()->getZoom());
    echo("= Effective light rig properties =");
    echo("Type: " + $threeDEffectiveData->getLightRig()->getLightType());
    echo("Direction: " + $threeDEffectiveData->getLightRig()->getDirection());
    echo("= Effective shape's top face relief properties =");
    echo("Type: " + $threeDEffectiveData->getBevelTop()->getBevelType());
    echo("Width: " + $threeDEffectiveData->getBevelTop()->getWidth());
    echo("Height: " + $threeDEffectiveData->getBevelTop()->getHeight());
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[ThreeDFormatEffectiveData](../../threedformateffectivedata)


---


