---
title: FormatText()
second_title: Aspose.Slides för C++ API-referens
description: Denna funktion anropas innan rendering av textavsnitt till SVG för att låta användaren kontrollera den resulterande SVG:n.
type: docs
weight: 1
url: /sv/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) metod


Denna funktion anropas innan rendering av textavsnitt till SVG för att låta användaren kontrollera den resulterande SVG:n.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Objekt för att kontrollera SVG tspan-generering. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Källavsnitt. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Källavsnittets textram. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISvgTSpan](../../isvgtspan/)
* Klass [IPortion](../../../aspose.slides/iportion/)
* Klass [ITextFrame](../../../aspose.slides/itextframe/)
* Klass [ISvgShapeAndTextFormattingController](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)