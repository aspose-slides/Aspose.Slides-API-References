---
title: WriteShapeStart()
second_title: Aspose.Slides für C++ API Referenz
description: Wird vor dem Rendern des Shapes aufgerufen. Wird einmal pro Shape aufgerufen. Wenn diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.
type: docs
weight: 66
url: /de/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) Methode

Wird vor dem Rendering von shape aufgerufen. Wird einmal pro shape aufgerufen. Wenn diese Funktion etwas an generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte html-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Ausgabeobjekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) die gerendert wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHtmlGenerator](../../ihtmlgenerator/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [EmbedAllFontsHtmlController](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)