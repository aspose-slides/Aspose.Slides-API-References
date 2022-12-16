---
title: insertClone
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 160
url: /php-java/slidecollection/insertclone/
---

## insertClone(int index, [Slide](../../slide) sourceSlide)  method

 Inserts a copy of a specified slide to specified position of the collection.
 

 The following example shows how to clone at another position within Presentation.
 
```php
  // Instantiate Presentation class that represents a presentation file
  $pres = new Presentation("CloneWithInSamePresentation.pptx");
  try {
    // Clone the desired slide to the end of the collection of slides in the same presentation
    $slds = $pres->getSlides();
    // Clone the desired slide to the specified index in the same presentation
    $slds->insertClone(2, $pres->getSlides()->get_Item(1));
    // Write the modified presentation to disk
    $pres->save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../../slide) | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #insertClone(int,ISlide,ILayoutSlide) or #insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

### Returns
[Slide](../../slide)


---


## insertClone(int index, [Slide](../../slide) sourceSlide, [LayoutSlide](../../layoutslide) destLayout)  method

 Inserts a copy of a specified slide to specified position of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destLayout | [LayoutSlide](../../layoutslide) | Layout slide for a new slide. |

### Returns
[Slide](../../slide)


---


## insertClone(int index, [Slide](../../slide) sourceSlide, [MasterSlide](../../masterslide) destMaster, boolean allowCloneMissingLayout)  method

 Inserts a copy of a specified source slide to specified position of the collection.
 Appropriate layout will be selected automatically from the specified 
 master (appropriate layout is the layout with the same Type or Name as 
 of layout of the source slide). If there is no appropriate layout then
 layout of the source slide will be cloned (if allowCloneMissingLayout 
 is true) or PptxEditException will be thrown (if allowCloneMissingLayout
 is false).
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destMaster | [MasterSlide](../masterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Returns
[Slide](../../slide)

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


