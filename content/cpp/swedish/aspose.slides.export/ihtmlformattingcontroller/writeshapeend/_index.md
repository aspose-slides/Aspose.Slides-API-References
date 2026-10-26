---
title: WriteShapeEnd()
second_title: Aspose.Slides för C++ API-referens
description: Kallas innan formens rendering. Kallas en gång per varje form. Om denna funktion skriver något till generatorn, kommer den aktuella bildgenereringen för bildspelet att avslutas, det tillagda HTML-fragmentet infogas och en ny bild startas ovanpå den föregående.
type: docs
weight: 66
url: /sv/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metod


Kallas innan formens renderering. Kallas en gång för varje form. Om denna funktion skriver något till generatorn, kommer den aktuella bildgenereringen för bildspelet att avslutas, det tillagda HTML-fragmentet infogas och en ny bild kommer att startas ovanpå den föregående.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
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
* Klass [IHtmlFormattingController](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)