---
title: addClone
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/slidecollection/addclone/
---

## addClone([Slide](../../Slide) sourceSlide)  method

 Adds a copy of a specified slide to the end of the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| sourceSlide | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #addClone(ISlide,ILayoutSlide) or #addClone(ISlide,IMasterSlide,boolean) for cloning slides, IGlobalLayoutSlideCollection#addClone(ILayoutSlide) or IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) for cloning layouts and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

### Returns
New slide.


---


## addClone([Slide](../../Slide) sourceSlide, [Section](../../Section) section)  method

 Adds a copy of a specified slide to the end of the specified section.
 

 
```php
  $presentation = new Presentation();
  try {
    $presentation->getSlides()->get_Item(0)->getShapes()->addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
    $presentation->getSections()->addSection("Section 1", $presentation->getSlides()->get_Item(0));
    $section2 = $presentation->getSections()->appendEmptySection("Section 2");
    $presentation->getSlides()->addClone($presentation->getSlides()->get_Item(0), $section2);
    // Now the second section contains a copy of the first slide.
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| sourceSlide | Slide to clone. |
| section | Section for a new slide. |

### Returns
New slide.

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | When section parameter contains wrong or invalid value. |


---


## addClone([Slide](../../Slide) sourceSlide, [LayoutSlide](../../LayoutSlide) destLayout)  method

 Adds a copy of a specified slide to the end of the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| sourceSlide | Slide to clone. |
| destLayout | Layout slide for a new slide. |

### Returns
New slide.


---


## addClone([Slide](../../Slide) sourceSlide, [MasterSlide](../../MasterSlide) destMaster, boolean allowCloneMissingLayout)  method

 Adds a copy of a specified source slide to the end of the collection.
 Appropriate layout will be selected automatically from the specified 
 master (appropriate layout is the layout with the same Type or Name as 
 of layout of the source slide). If there is no appropriate layout then
 layout of the source slide will be cloned (if allowCloneMissingLayout 
 is true) or PptxEditException will be thrown (if allowCloneMissingLayout
 is false).
 

### Parameters

| Name | Description |
| --- | --- |
| sourceSlide | Slide to clone. |
| destMaster | Master slide for a new slide. |
| allowCloneMissingLayout | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Returns
New slide.

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


