---
title: FormatText()
second_title: Aspose.Slides for C++ API Reference
description: This function is called before rendering of text portion to SVG to allow user to control resulting SVG.
type: docs
weight: 1
url: /aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) method


This function is called before rendering of text portion to SVG to allow user to control resulting SVG.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Object to control SVG tspan generation. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Source portion. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Source portion text frame. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISvgTSpan](../../isvgtspan/)
* Class [IPortion](../../../aspose.slides/iportion/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [ISvgShapeAndTextFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)