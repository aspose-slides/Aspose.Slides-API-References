---
title: SlideUtil
second_title: Aspose.Slides für C++ API-Referenz
description: Bietet Methoden, die bei der Suche nach Formen und Text in einer Präsentation helfen.
type: docs
weight: 14
url: /de/aspose.slides.util/slideutil/
---
## SlideUtil Klasse


Bietet Methoden, die bei der Suche nach Formen und Text in einer Präsentation helfen.

```cpp
class SlideUtil
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Ändert die Anordnung aller Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Ändert die Anordnung ausgewählter Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | Ändert die Anordnung aller Formen innerhalb einer Gruppierung. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Ändert die Anordnung ausgewählter Formen innerhalb einer Gruppierung. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | Findet und ersetzt Text in der Präsentation mit dem angegebenen Format |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | Findet Formen anhand des Alternativtexts in einer PPTX-Präsentation. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | Findet Formen anhand des Alternativtexts auf einer Folie in einer PPTX-Präsentation. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | Sucht alle Formen auf der angegebenen Folie, die dem angegebenen Platzhaltertyp entsprechen. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Gibt alle Textfelder auf einer Folie in einer PPTX-Präsentation zurück. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | Gibt alle Textfelder in einer PPTX-Präsentation zurück. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | Gibt alle Textfelder auf der angegebenen Folie zurück, die den angegebenen Text enthalten. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | Konvertiert ein Quelldateiformat in das entsprechende [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/). |

## Siehe auch

* Namensraum [Aspose::Slides::Util](../)
* Bibliothek [Aspose.Slides](../../)