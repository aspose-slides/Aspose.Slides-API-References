---
title: remove
type: docs
weight: 80
url: /php-java/layoutslide/remove/
---

# remove() method

 Removes layout from presentation.
 

##  Exception
PptxEditException Thrown if layout is already removed from presentation or if layout is used in presentation (its HasDependingSlides property is true). To avoid throwing of the PptxEditException check layout's HasDependingSlides property before.

