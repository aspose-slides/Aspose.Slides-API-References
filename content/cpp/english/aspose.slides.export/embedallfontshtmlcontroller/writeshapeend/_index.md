---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API Reference
description: Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.
type: docs
weight: 79
url: /aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) method


Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Output object. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) which is rendered last. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)