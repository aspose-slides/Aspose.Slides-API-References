---
title: SlideUtil
second_title: Aspose.Slides pro C++ API Reference
description: Nabízí metody, které pomáhají vyhledávat tvary a text v prezentaci.
type: docs
weight: 14
url: /cs/aspose.slides.util/slideutil/
---
## SlideUtil třída

Nabízí metody, které pomáhají vyhledávat tvary a text v prezentaci.

```cpp
class SlideUtil
```

## Metody

| Metoda | Popis |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Mění umístění všech tvarů na snímku. Zarovnává tvary k okrajům nebo ke kraji snímku nebo je zarovnává relativně vůči sobě navzájem. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Mění umístění vybraných tvarů na snímku. Zarovnává tvary k okrajům nebo ke kraji snímku nebo je zarovnává relativně vůči sobě navzájem. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | Mění umístění všech tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo ke kraji snímku nebo je zarovnává relativně vůči sobě navzájem. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Mění umístění vybraných tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo ke kraji snímku nebo je zarovnává relativně vůči sobě navzájem. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | Vyhledá a nahradí text v prezentaci s daným formátem |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | Vyhledá tvar podle alternativního textu v PPTX prezentaci. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | Vyhledá tvar podle alternativního textu na snímku v PPTX prezentaci. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | Vyhledá všechny tvary na určeném snímku, které odpovídají danému typu zástupce. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Vrací všechny textové rámy na snímku v PPTX prezentaci. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | Vrací všechny textové rámy v PPTX prezentaci. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | Vrací všechny textové rámy na určeném snímku, které obsahují daný text. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | Převede zdrojový formát souboru do odpovídajícího [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/). |
## Viz také

* Jmenný prostor [Aspose::Slides::Util](../)
* Knihovna [Aspose.Slides](../../)