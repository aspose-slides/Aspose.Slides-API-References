---
title: WriteShapeEnd()
second_title: Aspose.Slides für C++ API Referenz
description: Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung abgeschlossen, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.
type: docs
weight: 79
url: /de/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) Methode

Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung abgeschlossen, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Ausgabeobjekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) die zuletzt gerendert wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHtmlGenerator](../../ihtmlgenerator/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [EmbedAllFontsHtmlController](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)