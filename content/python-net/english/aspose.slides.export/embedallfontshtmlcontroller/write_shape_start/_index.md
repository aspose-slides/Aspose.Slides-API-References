---
title: write_shape_start method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---


## write_shape_start {#asposeslidesexportihtmlgenerator-asposeslidesishape}
Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/aspose.slides.export/ihtmlgenerator) | Output object. |
| shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | Shape which is about to render. |



### See Also
* class [`EmbedAllFontsHtmlController`](/slides/python-net/aspose.slides.export/embedallfontshtmlcontroller)
* class [`IHtmlGenerator`](/slides/python-net/aspose.slides.export/ihtmlgenerator)
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

