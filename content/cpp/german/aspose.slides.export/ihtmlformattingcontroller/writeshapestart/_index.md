---
title: WriteShapeStart()
second_title: Aspose.Slides für C++ API-Referenz
description: Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.
type: docs
weight: 53
url: /de/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) Methode


Wird vor dem Rendern der Form aufgerufen. Wird einmal pro Form aufgerufen. Falls diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über dem vorherigen gestartet.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Ausgabeobjekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/), das gerendert werden soll. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IHtmlFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)