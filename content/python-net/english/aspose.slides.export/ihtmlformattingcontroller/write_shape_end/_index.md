﻿---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---


## write_shape_end {#ihtmlgenerator-ishape}
Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/aspose.slides.export/ihtmlgenerator) | Output object. |
| shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | Shape which is rendered last. |



### See Also
* class [`IHtmlFormattingController`](/slides/python-net/aspose.slides.export/ihtmlformattingcontroller)
* class [`IHtmlGenerator`](/slides/python-net/aspose.slides.export/ihtmlgenerator)
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

