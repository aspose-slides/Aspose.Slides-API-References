---
title: WriteShapeEnd()
second_title: Aspose.Slides für C++ API-Referenz
description: Wird vor dem Rendern der Form aufgerufen. Wird für jede Form einmal aufgerufen. Wenn diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild wird über dem vorherigen gestartet.
type: docs
weight: 66
url: /de/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) Methode

Wird vor dem Rendern von shape aufgerufen. Wird für jede shape einmal aufgerufen. Wenn diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild wird über dem vorherigen gestartet.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
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
* Klasse [IHtmlFormattingController](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)