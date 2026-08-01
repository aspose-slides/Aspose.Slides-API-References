---
title: WriteShapeEnd()
second_title: Aspose.Slides voor C++ API-referentie
description: Wordt aangeroepen vóór het renderen van een shape. Wordt één keer per shape aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige generatie van de slide-afbeelding voltooid, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding gestart bovenop de vorige.
type: docs
weight: 79
url: /nl/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) methode

Wordt aangeroepen vóór het renderen van shape. Wordt eenmaal per elke shape aangeroepen. Als deze functie iets naar generator schrijft, wordt de huidige slide-afbeeldingsgeneratie voltooid, wordt het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding gestart bovenop de vorige.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Output object. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) die als laatste wordt gerenderd. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHtmlGenerator](../../ihtmlgenerator/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [EmbedAllFontsHtmlController](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)