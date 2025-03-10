---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API Reference
description: Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.
type: docs
weight: 53
url: /aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) method


Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Output object. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) which is about to render. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IHtmlFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)