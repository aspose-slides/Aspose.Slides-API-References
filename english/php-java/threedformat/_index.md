---
title: ThreeDFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/threedformat/
---

## ThreeDFormat class

 Represents 3-D properties.
 

 The following example shows how to add 3D shape in PowerPoint Presentation.
 
```php
  // Create an instance of Presentation class.
  $pres = new Presentation();
  try {
    // Add a shape using AddAutoShape method
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
    // Define TextFrame and its properties
    $shape->getTextFrame()->setText("3D");
    $shape->getTextFrame()->getParagraphs()->get_Item(0)->getParagraphFormat()->getDefaultPortionFormat()->setFontHeight(64);
    // Define ThreeDFormat Properties
    $shape->getThreeDFormat()->getCamera()->setCameraType(CameraPresetType.OrthographicFront);
    $shape->getThreeDFormat()->getCamera()->setRotation(20, 30, 40);
    $shape->getThreeDFormat()->getLightRig()->setLightType(LightRigPresetType.Flat);
    $shape->getThreeDFormat()->getLightRig()->setDirection(LightingDirection.Top);
    $shape->getThreeDFormat()->setMaterial(MaterialPresetType.Flat);
    $shape->getThreeDFormat()->setExtrusionHeight(100);
    $shape->getThreeDFormat()->getExtrusionColor()->setColor(Color::BLUE);
    // Save the Presentation file
    $pres->save("sandbox_3d.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Methods

| Name | Description |
| --- | --- |
| [getBevelBottom](getbevelbottom)() | Returns or sets the type of a bottom 3D bevel. Read-only IShapeBevel. |
| [getBevelTop](getbeveltop)() | Returns or sets the type of a top 3D bevel. Read-only IShapeBevel. |
| [getCamera](getcamera)() | Returns or sets the settings of a camera. Read-only ICamera. |
| [getContourColor](getcontourcolor)() | Returns or sets the color of a contour. Read-only IColorFormat. |
| [getContourWidth](getcontourwidth)() | Returns or sets the width of a 3D contour. Read/write double. |
| [getDepth](getdepth)() | Returns or sets the depth of a 3D shape. Read/write double. |
| [getEffective](geteffective)() | Gets effective 3-D formatting data with the inheritance applied. |
| [getExtrusionColor](getextrusioncolor)() | Returns or sets the color of an extrusion. Read-only IColorFormat. |
| [getExtrusionHeight](getextrusionheight)() | Returns or sets the height of an extrusion effect. Read/write double. |
| [getLightRig](getlightrig)() | Returns or sets the type of a light. Read-only ILightRig. |
| [getMaterial](getmaterial)() | Returns or sets the type of a material. Read/write MaterialPresetType. |
| [setContourWidth](setcontourwidth)(double) | Returns or sets the width of a 3D contour. Read/write double. |
| [setDepth](setdepth)(double) | Returns or sets the depth of a 3D shape. Read/write double. |
| [setExtrusionHeight](setextrusionheight)(double) | Returns or sets the height of an extrusion effect. Read/write double. |
| [setMaterial](setmaterial)(int) | Returns or sets the type of a material. Read/write MaterialPresetType. |
