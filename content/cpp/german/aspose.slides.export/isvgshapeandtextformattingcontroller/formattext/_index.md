---
title: FormatText()
second_title: Aspose.Slides für C++ API-Referenz
description: Diese Funktion wird vor dem Rendern des Textabschnitts nach SVG aufgerufen, um dem Benutzer die Kontrolle über das resultierende SVG zu ermöglichen.
type: docs
weight: 1
url: /de/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) Methode

Diese Funktion wird vor dem Rendern des Textabschnitts nach SVG aufgerufen, um dem Benutzer die Kontrolle über das resultierende SVG zu ermöglichen.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Objekt zur Steuerung der SVG-tspan-Erstellung. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Quellabschnitt. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Textfeld des Quellabschnitts. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISvgTSpan](../../isvgtspan/)
* Klasse [IPortion](../../../aspose.slides/iportion/)
* Klasse [ITextFrame](../../../aspose.slides/itextframe/)
* Klasse [ISvgShapeAndTextFormattingController](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)