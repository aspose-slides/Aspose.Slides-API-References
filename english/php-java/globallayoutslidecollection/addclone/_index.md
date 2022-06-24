---
title: addClone
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 20
url: /php-java/globallayoutslidecollection/addclone/
---

## addClone(com.aspose.slides.ILayoutSlide) method

 Adds a copy of a specified layout slide to the presentation.
 

### Parameters

| Name | Description |
| --- | --- |
| sourceLayout | Slide to clone. When cloning a layout between different presentations layout's master can be cloned too to keep source formatting. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. |

### Returns
Added slide.


---


## addClone(com.aspose.slides.ILayoutSlide, com.aspose.slides.IMasterSlide) method

 Adds a copy of a specified layout slide to the presentation.
 

### Parameters

| Name | Description |
| --- | --- |
| sourceLayout | Slide to clone. |
| destMaster | Master slide for a new layout. 1) New layout will be linked with defined master in destination presentation. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. 2) Analogue of this method is method IMasterLayoutSlideCollection#addClone(ILayoutSlide) accessed with ( IMasterSlide#getLayoutSlides) property. |

### Returns
Added slide.


---


