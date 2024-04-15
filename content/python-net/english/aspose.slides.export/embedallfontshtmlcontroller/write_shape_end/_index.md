---
title: write_shape_end method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---


## write_shape_end {#ihtmlgenerator-ishape}
Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| generator | IHtmlGenerator | Output object. |
| shape | IShape | Shape which is rendered last. |



### See Also
* class [`EmbedAllFontsHtmlController`](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)
