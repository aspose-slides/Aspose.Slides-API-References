---
title: WriteShapeEnd()
second_title: Aspose.Slides voor C++ API-referentie
description: Wordt aangeroepen vóór het renderen van de vorm. Wordt eenmaal per elke vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldinggeneratie voltooid, wordt het toegevoegde HTML-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.
type: docs
weight: 66
url: /nl/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) method

Wordt aangeroepen vóór het renderen van de vorm. Wordt eenmaal per elke vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-afbeeldinggeneratie afgerond, wordt het toegevoegde HTML-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Uitvoerobject. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) die als laatste wordt gerenderd. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHtmlGenerator](../../ihtmlgenerator/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [IHtmlFormattingController](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)