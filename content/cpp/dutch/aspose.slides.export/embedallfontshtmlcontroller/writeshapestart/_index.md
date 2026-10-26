---
title: WriteShapeStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Aangeroepen vóór het renderen van de vorm. Eén keer per vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-beeldgeneratie voltooid, het toegevoegde html-fragment ingevoegd en wordt een nieuw beeld bovenop het vorige gestart.
type: docs
weight: 66
url: /nl/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) methode


Aangeroepen vóór het renderen van de vorm. Eén keer per vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige slide-beeldgeneratie afgerond, het toegevoegde html-fragment ingevoegd en een nieuw beeld wordt bovenop het vorige gestart.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Uitvoerobject. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) die op het punt staat te renderen. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHtmlGenerator](../../ihtmlgenerator/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [EmbedAllFontsHtmlController](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)