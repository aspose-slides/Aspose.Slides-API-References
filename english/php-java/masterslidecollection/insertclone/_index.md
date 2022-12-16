---
title: insertClone
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/masterslidecollection/insertclone/
---

## insertClone(int index, [MasterSlide](../../masterslide) sourceMaster)  method

 Inserts a copy of a specified master slide to specified position of the collection.
 Linked layout slides will be copied too.
 

 The following example shows how to clone master slide in another PowerPoint Presentation.
 
```php
  // Instantiate Presentation class to load the source presentation file
  $srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
  try {
    // Instantiate Presentation class for destination presentation (where slide is to be cloned)
    $destPres = new Presentation();
    try {
      // Instantiate ISlide from the collection of slides in source presentation along with
      // Master slide
      $SourceSlide = $srcPres->getSlides()->get_Item(0);
      $SourceMaster = $SourceSlide->getLayoutSlide()->getMasterSlide();
      // Get Master Slides of destination presentation
      $masters = $destPres->getMasters();
      // Clone the desired master slide from the source presentation to the collection of masters in the
      // Destination presentation
      $iSlide = $masters->addClone($SourceMaster);
      // Collection of slides in the destination presentation
      $slds = $destPres->getSlides();
      // Clone source slide to destination slides collection.
      $slds->addClone($SourceSlide, $iSlide, true);
      // Save the destination presentation to disk
      $destPres->save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
    } finally {
      if ($destPres != null) {
        $destPres->dispose();
      }
    }
  } finally {
    if ($srcPres != null) {
      $srcPres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceMaster | [MasterSlide](../../masterslide) | Slide to clone. |

### Returns
[MasterSlide](../../masterslide)


---


