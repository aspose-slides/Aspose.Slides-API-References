---
title: WriteShapeStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Aangeroepen vóór het renderen van de shape. Eenmaal per shape aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie voltooid, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.
type: docs
weight: 53
url: /nl/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) methode

Aangeroepen vóór de rendering van de shape. Eenmaal per elke shape aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldingsgeneratie voltooid, het toegevoegde HTML-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Uitvoerobject. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) die gaat renderen. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHtmlGenerator](../../ihtmlgenerator/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [IHtmlFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)