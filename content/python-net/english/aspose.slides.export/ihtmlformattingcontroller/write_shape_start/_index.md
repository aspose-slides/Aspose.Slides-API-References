---
title: write_shape_start method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---


## write_shape_start {#ihtmlgenerator-ishape}
Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| generator | IHtmlGenerator | Output object. |
| shape | IShape | Shape which is about to render. |



### See Also
* class [`IHtmlFormattingController`](/slides/python-net/aspose.slides.export/ihtmlformattingcontroller)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)
