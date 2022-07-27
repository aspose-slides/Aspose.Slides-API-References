---
title: alignShapes
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/slideutil/alignshapes/
---

## alignShapes(int alignmentType, boolean alignToSlide, [ShapeCollection](../../shapecollection) shapes)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges |
| shapes | [ShapeCollection](../../shapecollection) | Shapes collection to be aligned |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [MasterHandoutSlide](../../masterhandoutslide) slide)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [MasterHandoutSlide](../../masterhandoutslide) | Parent slide. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [LayoutSlide](../../layoutslide) slide)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [LayoutSlide](../../layoutslide) | Parent slide. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [Slide](../../slide) slide)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [Slide](../../slide) | Parent slide. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [MasterSlide](../../masterslide) slide)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [MasterSlide](../../masterslide) | Parent slide. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [NotesSlide](../../notesslide) slide)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [NotesSlide](../../notesslide) | Parent slide. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [MasterNotesSlide](../../masternotesslide) slide)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [MasterNotesSlide](../../masternotesslide) | Parent slide. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [MasterHandoutSlide](../../masterhandoutslide) slide, int[] shapeIndexes)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [MasterHandoutSlide](../masterhandoutslide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [LayoutSlide](../../layoutslide) slide, int[] shapeIndexes)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [LayoutSlide](../layoutslide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [Slide](../../slide) slide, int[] shapeIndexes)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [Slide](../slide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [MasterSlide](../../masterslide) slide, int[] shapeIndexes)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [MasterSlide](../masterslide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [NotesSlide](../../notesslide) slide, int[] shapeIndexes)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [NotesSlide](../notesslide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [MasterNotesSlide](../../masternotesslide) slide, int[] shapeIndexes)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [MasterNotesSlide](../masternotesslide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [GroupShape](../../groupshape) groupShape)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [GroupShape](../../groupshape) | Parent group shape. |

### Returns
void


---


## alignShapes(int alignmentType, boolean alignToSlide, [GroupShape](../../groupshape) groupShape, int[] shapeIndexes)  method

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

| Name | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [GroupShape](../groupshape) | Parent group shape. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### Returns
void


---


