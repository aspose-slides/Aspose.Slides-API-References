---
title: insertClone
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 160
url: /php-java/slidecollection/insertclone/
---

## insertClone(int, com.aspose.slides.ISlide) method

 Inserts a copy of a specified slide to specified position of the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| index | Index of new slide. |
| sourceSlide | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #insertClone(int,ISlide,ILayoutSlide) or #insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

### Returns
Inserted slide.


---


## insertClone(int, com.aspose.slides.ISlide, com.aspose.slides.ILayoutSlide) method

 Inserts a copy of a specified slide to specified position of the collection.
 

### Parameters

| Name | Description |
| --- | --- |
| index | Index of new slide. |
| sourceSlide | Slide to clone. |
| destLayout | Layout slide for a new slide. |

### Returns
Inserted slide.


---


## insertClone(int, com.aspose.slides.ISlide, com.aspose.slides.IMasterSlide, boolean) method

 Inserts a copy of a specified source slide to specified position of the collection.
 Appropriate layout will be selected automatically from the specified 
 master (appropriate layout is the layout with the same Type or Name as 
 of layout of the source slide). If there is no appropriate layout then
 layout of the source slide will be cloned (if allowCloneMissingLayout 
 is true) or PptxEditException will be thrown (if allowCloneMissingLayout
 is false).
 

### Parameters

| Name | Description |
| --- | --- |
| index | Index of new slide. |
| sourceSlide | Slide to clone. |
| destMaster | Master slide for a new slide. |
| allowCloneMissingLayout | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Returns
Inserted slide.

### Exception

| Exception | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


