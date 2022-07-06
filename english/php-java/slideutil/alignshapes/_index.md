---
title: alignShapes
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/slideutil/alignshapes/
---

## alignShapes(int alignmentType, boolean alignToSlide, [../../ShapeCollection]ShapeCollection shapes)  method

 Changes the placement of all shapes in the collection. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, true, $pres->getSlides()->get_Item(0)->getShapes());
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges |
| shapes | Shapes collection to be aligned |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../BaseSlide]BaseSlide slide)  method

 Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, true, $pres->getSlides()->get_Item(0));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../LayoutSlide]LayoutSlide slide)  method

 Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, true, $pres->getSlides()->get_Item(0));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../MasterHandoutSlide]MasterHandoutSlide slide)  method

 Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, true, $pres->getSlides()->get_Item(0));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../MasterNotesSlide]MasterNotesSlide slide)  method

 Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, true, $pres->getSlides()->get_Item(0));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../MasterSlide]MasterSlide slide)  method

 Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, true, $pres->getSlides()->get_Item(0));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../NotesSlide]NotesSlide slide)  method

 Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, true, $pres->getSlides()->get_Item(0));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../Slide]Slide slide)  method

 Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, true, $pres->getSlides()->get_Item(0));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../BaseSlide]BaseSlide slide, int[] shapeIndexes)  method

  Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
  or align them relative to each other.
  
Example:
  
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape1 = $slide->getShapes()->get_Item(0);
    $shape2 = $slide->getShapes()->get_Item(1);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, false, $pres->getSlides()->get_Item(0), new int[]{ $slide->getShapes()->indexOf($shape1), $slide->getShapes()->indexOf($shape2) });
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |
| shapeIndexes | Indexes of shapes to be aligned. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../LayoutSlide]LayoutSlide slide, int[] shapeIndexes)  method

  Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
  or align them relative to each other.
  
Example:
  
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape1 = $slide->getShapes()->get_Item(0);
    $shape2 = $slide->getShapes()->get_Item(1);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, false, $pres->getSlides()->get_Item(0), new int[]{ $slide->getShapes()->indexOf($shape1), $slide->getShapes()->indexOf($shape2) });
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |
| shapeIndexes | Indexes of shapes to be aligned. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../MasterHandoutSlide]MasterHandoutSlide slide, int[] shapeIndexes)  method

  Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
  or align them relative to each other.
  
Example:
  
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape1 = $slide->getShapes()->get_Item(0);
    $shape2 = $slide->getShapes()->get_Item(1);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, false, $pres->getSlides()->get_Item(0), new int[]{ $slide->getShapes()->indexOf($shape1), $slide->getShapes()->indexOf($shape2) });
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |
| shapeIndexes | Indexes of shapes to be aligned. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../MasterNotesSlide]MasterNotesSlide slide, int[] shapeIndexes)  method

  Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
  or align them relative to each other.
  
Example:
  
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape1 = $slide->getShapes()->get_Item(0);
    $shape2 = $slide->getShapes()->get_Item(1);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, false, $pres->getSlides()->get_Item(0), new int[]{ $slide->getShapes()->indexOf($shape1), $slide->getShapes()->indexOf($shape2) });
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |
| shapeIndexes | Indexes of shapes to be aligned. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../MasterSlide]MasterSlide slide, int[] shapeIndexes)  method

  Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
  or align them relative to each other.
  
Example:
  
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape1 = $slide->getShapes()->get_Item(0);
    $shape2 = $slide->getShapes()->get_Item(1);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, false, $pres->getSlides()->get_Item(0), new int[]{ $slide->getShapes()->indexOf($shape1), $slide->getShapes()->indexOf($shape2) });
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |
| shapeIndexes | Indexes of shapes to be aligned. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../NotesSlide]NotesSlide slide, int[] shapeIndexes)  method

  Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
  or align them relative to each other.
  
Example:
  
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape1 = $slide->getShapes()->get_Item(0);
    $shape2 = $slide->getShapes()->get_Item(1);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, false, $pres->getSlides()->get_Item(0), new int[]{ $slide->getShapes()->indexOf($shape1), $slide->getShapes()->indexOf($shape2) });
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |
| shapeIndexes | Indexes of shapes to be aligned. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../Slide]Slide slide, int[] shapeIndexes)  method

  Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
  or align them relative to each other.
  
Example:
  
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $shape1 = $slide->getShapes()->get_Item(0);
    $shape2 = $slide->getShapes()->get_Item(1);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignBottom, false, $pres->getSlides()->get_Item(0), new int[]{ $slide->getShapes()->indexOf($shape1), $slide->getShapes()->indexOf($shape2) });
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| slide | Parent slide. |
| shapeIndexes | Indexes of shapes to be aligned. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../GroupShape]GroupShape groupShape)  method

 Changes the placement of all shapes within group shape. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignLeft, false, $slide->getShapes()->get_Item(0));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| groupShape | Parent group shape. |


---


## alignShapes(int alignmentType, boolean alignToSlide, [../../GroupShape]GroupShape groupShape, int[] shapeIndexes)  method

 Changes the placement of selected shapes within group shape. Aligns shapes to the margins or the edge of the slide
 or align them relative to each other.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $slide = $pres->getSlides()->get_Item(0);
    SlideUtil->alignShapes(ShapesAlignmentType.AlignLeft, false, $slide->getShapes()->get_Item(0), new int[]{ 0, 2 });
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| alignmentType | Determines which type of alignment will be applied. |
| alignToSlide | If true, shapes will be aligned relative to the slide edges. |
| groupShape | Parent group shape. |
| shapeIndexes | Indexes of shapes to be aligned. |


---


