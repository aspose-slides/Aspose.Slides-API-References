---
title: WriteShapeStart()
second_title: Aspose.Slides för C++ API-referens
description: Kallas innan figurens rendering. Kallas en gång per varje figur. Om den här funktionen skriver något till generatorn, avslutas den aktuella bildgenereringen för bilden, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den föregående.
type: docs
weight: 66
url: /sv/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metod

Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Utdatam objekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) som är på väg att renderas. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IHtmlGenerator](../../ihtmlgenerator/)
* Klass [IShape](../../../aspose.slides/ishape/)
* Klass [EmbedAllFontsHtmlController](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)