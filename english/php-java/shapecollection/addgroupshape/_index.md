---
title: addGroupShape
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 140
url: /php-java/shapecollection/addgroupshape/
---

## addGroupShape()  method

 Creates a new GroupShape and adds it to the end of the collection.
 GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape.
 

 The following example shows how to add a group shape to a slide of PowerPoint Presentation.
 
```php
  // Instantiate Presentation class
  $pres = new Presentation();
  try {
    // Get the first slide
    $sld = $pres->getSlides()->get_Item(0);
    // Accessing the shape collection of slides
    $slideShapes = $sld->getShapes();
    // Adding a group shape to the slide
    $groupShape = $slideShapes->addGroupShape();
    // Adding shapes inside added group shape
    $groupShape->getShapes()->addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
    $groupShape->getShapes()->addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
    $groupShape->getShapes()->addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
    $groupShape->getShapes()->addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
    // Adding group shape frame
    $groupShape->setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool::False, NullableBool::False, 0));
    // Write the PPTX file to disk
    $pres->save("GroupShape_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[GroupShape](../../groupshape)


---


## addGroupShape([SvgImage](../../svgimage) svgImage, float x, float y, float width, float height)  method

 Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | Svg image object ISvgImage |
| x | float | The X coordinate for the left side of the shape group frame. |
| y | float | The Y coordinate for the top side of the shape group frame. |
| width | float | The width of the group of the shape group frame. |
| height | float | The height of a group of the shape group frame. |

### Returns
[GroupShape](../../groupshape)


---


