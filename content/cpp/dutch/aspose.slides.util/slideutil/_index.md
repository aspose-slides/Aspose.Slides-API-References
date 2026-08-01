---
title: SlideUtil
second_title: Aspose.Slides voor C++ API Referentie
description: Biedt methoden die helpen bij het zoeken naar vormen en tekst in een presentatie.
type: docs
weight: 14
url: /nl/aspose.slides.util/slideutil/
---
## SlideUtil klasse


Biedt methoden die helpen bij het zoeken naar vormen en tekst in een presentatie.

```cpp
class SlideUtil
```

## Methoden

| Method | Description |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Wijzigt de plaatsing van alle vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia of uitricht ze ten opzichte van elkaar. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Wijzigt de plaatsing van geselecteerde vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia of uitricht ze ten opzichte van elkaar. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | Wijzigt de plaatsing van alle vormen binnen een groepsvorm. Lijnt vormen uit op de marges of de rand van de dia of uitricht ze ten opzichte van elkaar. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Wijzigt de plaatsing van geselecteerde vormen binnen een groepsvorm. Lijnt vormen uit op de marges of de rand van de dia of uitricht ze ten opzichte van elkaar. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | Zoekt en vervangt tekst in de presentatie met het opgegeven formaat |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | Vindt vorm op basis van alternatieve tekst in een PPTX-presentatie. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | Vindt vorm op basis van alternatieve tekst op een dia in een PPTX-presentatie. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | Zoekt alle vormen op de opgegeven dia die overeenkomen met het opgegeven placeholder-type. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Geeft alle tekstframes op een dia in een PPTX-presentatie terug. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | Geeft alle tekstframes in een PPTX-presentatie terug. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | Geeft alle tekstframes op de opgegeven dia terug die de opgegeven tekst bevatten. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | Converteert een bronbestandformaat naar de overeenkomstige [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/). |
## Zie ook

* Namespace [Aspose::Slides::Util](../)
* Library [Aspose.Slides](../../)