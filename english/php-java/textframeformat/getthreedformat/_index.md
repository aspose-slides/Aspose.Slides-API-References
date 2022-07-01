---
title: getThreeDFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 160
url: /php-java/textframeformat/getthreedformat/
---

## getThreeDFormat()  method

 Returns the ThreeDFormat object that represents 3d effect properties for a text.
 Read-only  IThreeDFormat.
 

 
```php
  $pres = new Presentation();
  try {
    $autoShape = $pres->getSlides()->get_Item(0)->getShapes()->addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
    $textFrame = $autoShape->getTextFrame();
    $textFrame->setText("Aspose.Slide Test Text");
    // Set text transformation
    $textFrame->getTextFrameFormat()->setTransform(TextShapeType.ArchUpPour);
    // Set Extrusion
    $textFrame->getTextFrameFormat()->getThreeDFormat()->getExtrusionColor()->setColor(Color::ORANGE);
    $textFrame->getTextFrameFormat()->getThreeDFormat()->setExtrusionHeight(6);
    // Set Contour
    $textFrame->getTextFrameFormat()->getThreeDFormat()->getContourColor()->setColor(Color::DARK_GRAY);
    $textFrame->getTextFrameFormat()->getThreeDFormat()->setContourWidth(1.5);
    // Set Depth
    $textFrame->getTextFrameFormat()->getThreeDFormat()->setDepth(3);
    // Set Material
    $textFrame->getTextFrameFormat()->getThreeDFormat()->setMaterial(MaterialPresetType.Plastic);
    // Set Lighting
    $textFrame->getTextFrameFormat()->getThreeDFormat()->getLightRig()->setDirection(LightingDirection.Top);
    $textFrame->getTextFrameFormat()->getThreeDFormat()->getLightRig()->setLightType(LightRigPresetType.Balanced);
    $textFrame->getTextFrameFormat()->getThreeDFormat()->getLightRig()->setRotation(0, 0, 40);
    // Set camera type
    $textFrame->getTextFrameFormat()->getThreeDFormat()->getCamera()->setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
IThreeDFormat


---


