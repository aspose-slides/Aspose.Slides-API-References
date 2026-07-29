---
title: WriteShapeEnd()
second_title: Aspose.Slides för C++ API-referens
description: Kallas innan formens rendering. Kallas en gång per varje form. Om den här funktionen skriver något till generatorn, avslutas den aktuella bildgenereringen för bilden, det lagda html-fragmentet infogas och en ny bild startas ovanpå den föregående.
type: docs
weight: 79
url: /sv/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metod


Kallas innan formens rendering. Kallas en gång per varje form. Om den här funktionen skriver något till generatorn, kommer den aktuella bildgenereringen för bilden att avslutas, den lagda html-fragmentet infogas och en ny bild startas ovanpå den föregående.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Utdataobjekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) som renderas sist. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IHtmlGenerator](../../ihtmlgenerator/)
* Klass [IShape](../../../aspose.slides/ishape/)
* Klass [EmbedAllFontsHtmlController](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)