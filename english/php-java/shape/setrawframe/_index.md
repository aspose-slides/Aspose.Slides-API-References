---
title: setRawFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 460
url: /php-java/shape/setrawframe/
---

## setRawFrame([ShapeFrame](../../shapeframe) value)  method

 Returns or sets the raw shape frame's properties.
 Read/write  IShapeFrame.
 

 Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sence in general case (particulary in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
 
```php
  $shape = $$missing$;
  $shape->setFrame(new ShapeFrame(Float::NaN, Float::NaN, Float::NaN, Float::NaN, NullableBool::NotDefined, NullableBool::NotDefined, Float::NaN));
  // or
  $slide->getShapes()->addAutoShape(ShapeType.RoundCornerRectangle, Float::NaN, Float::NaN, Float::NaN, Float::NaN);
  // Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
  // This applies to these use cases:
  $shape = $$missing$;
  $shape->setFrame();// cannot be undefined

  $shapes = $$missing$;
  // x, y, width, height parameters cannot be Float.NaN:
  {
    $shapes->addAudioFrameCD();
    $shapes->addAudioFrameEmbedded();
    $shapes->addAudioFrameLinked();
    $shapes->addAutoShape();
    $shapes->addChart();
    $shapes->addConnector();
    $shapes->addOleObjectFrame();
    $shapes->addPictureFrame();
    $shapes->addSmartArt();
    $shapes->addTable();
    $shapes->addVideoFrame();
    $shapes->insertAudioFrameEmbedded();
    $shapes->insertAudioFrameLinked();
    $shapes->insertAutoShape();
    $shapes->insertChart();
    $shapes->insertConnector();
    $shapes->insertOleObjectFrame();
    $shapes->insertPictureFrame();
    $shapes->insertTable();
    $shapes->insertVideoFrame();
  }
  // But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
  $shape = $$missing$;// shape is linked to placeholder

  $shape->setRawFrame(new ShapeFrame(Float::NaN, Float::NaN, 100, Float::NaN, NullableBool::NotDefined, NullableBool::NotDefined, 0));// now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}

```

### Returns
void


---


