---
title: FormatText()
second_title: Aspose.Slides voor C++ API-referentie
description: Deze functie wordt aangeroepen vóór het renderen van een tekstdeel naar SVG om de gebruiker in staat te stellen de resulterende SVG te beheersen.
type: docs
weight: 1
url: /nl/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) methode

Deze functie wordt aangeroepen vóór het renderen van een tekstdeel naar SVG om de gebruiker de mogelijkheid te geven de resulterende SVG te beheersen.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Object om de generatie van SVG tspan te beheersen. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Brongedeelte. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Tekstkader van het brongedeelte. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISvgTSpan](../../isvgtspan/)
* Klasse [IPortion](../../../aspose.slides/iportion/)
* Klasse [ITextFrame](../../../aspose.slides/itextframe/)
* Klasse [ISvgShapeAndTextFormattingController](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)