---
title: addClone
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidecollection/addclone/
---

## addClone([Slide](../../slide) sourceSlide)  function

 Adds a copy of a specified slide to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../../slide) | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #addClone(ISlide,ILayoutSlide) or #addClone(ISlide,IMasterSlide,boolean) for cloning slides, IGlobalLayoutSlideCollection#addClone(ILayoutSlide) or IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) for cloning layouts and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

### Result
[Slide](../../slide)


---


## addClone([Slide](../../slide) sourceSlide, [Section](../../section) section)  function

 Adds a copy of a specified slide to the end of the specified section.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| section | [Section](../../section) | Section for a new slide. |

### Result
[Slide](../../slide)

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | When section parameter contains wrong or invalid value. |


---


## addClone([Slide](../../slide) sourceSlide, [LayoutSlide](../../layoutslide) destLayout)  function

 Adds a copy of a specified slide to the end of the collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destLayout | [LayoutSlide](../../layoutslide) | Layout slide for a new slide. |

### Result
[Slide](../../slide)


---


## addClone([Slide](../../slide) sourceSlide, [MasterSlide](../../masterslide) destMaster, boolean allowCloneMissingLayout)  function

 Adds a copy of a specified source slide to the end of the collection.
 Appropriate layout will be selected automatically from the specified 
 master (appropriate layout is the layout with the same Type or Name as 
 of layout of the source slide). If there is no appropriate layout then
 layout of the source slide will be cloned (if allowCloneMissingLayout 
 is true) or PptxEditException will be thrown (if allowCloneMissingLayout
 is false).
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destMaster | [MasterSlide](../masterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Result
[Slide](../../slide)

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


