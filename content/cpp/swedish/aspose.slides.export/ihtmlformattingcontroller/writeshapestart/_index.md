---
title: WriteShapeStart()
second_title: Aspose.Slides för C++ API-referens
description: Kallas innan formens rendering. Kallas en gång för varje form. Om den här funktionen skriver något till generatorn, avslutas den aktuella bildgenereringen för bilden, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den föregående.
type: docs
weight: 53
url: /sv/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metod

Kallas innan formens rendering. Kallas en gång för varje form. Om den här funktionen skriver något till generatorn avslutas den aktuella bildgenereringen för bilden, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den föregående.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Utdataobjekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) som är på väg att renderas. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IHtmlGenerator](../../ihtmlgenerator/)
* Klass [IShape](../../../aspose.slides/ishape/)
* Klass [IHtmlFormattingController](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)