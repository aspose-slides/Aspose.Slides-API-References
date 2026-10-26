---
title: SlideUtil
second_title: Aspose.Slides for C++ API Referencia
description: Metódusokat kínál, amelyek segítenek alakzatok és szöveg keresésében egy prezentációban.
type: docs
weight: 14
url: /hu/aspose.slides.util/slideutil/
---
## SlideUtil osztály

Olyan módszereket kínál, amelyek segítenek alakzatok és szöveg keresésében egy prezentációban.

```cpp
class SlideUtil
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Megváltoztatja az összes alakzat elhelyezését a dián. Az alakzatok elrendezése a margókhoz vagy a dia széléhez történik, vagy egymáshoz viszonyítva igazítja őket. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Megváltoztatja a kijelölt alakzatok elhelyezését a dián. Az alakzatok elrendezése a margókhoz vagy a dia széléhez történik, vagy egymáshoz viszonyítva igazítja őket. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | Megváltoztatja az összes alakzat elhelyezését a csoport alakzaton belül. Az alakzatok elrendezése a margókhoz vagy a dia széléhez történik, vagy egymáshoz viszonyítva igazítja őket. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Megváltoztatja a kijelölt alakzatok elhelyezését a csoport alakzaton belül. Az alakzatok elrendezése a margókhoz vagy a dia széléhez történik, vagy egymáshoz viszonyítva igazítja őket. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | Keres és helyettesít szöveget a prezentációban a megadott formátummal |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | Alakzat keresése alternatív szöveggel egy PPTX prezentációban. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | Alakzat keresése alternatív szöveggel egy dián egy PPTX prezentációban. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | Az összes alakzat keresése a megadott dián, amely megfelel a megadott helyőrző típusnak. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Visszaadja az összes szövegdobozt egy dián egy PPTX prezentációban. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | Visszaadja az összes szövegdobozt egy PPTX prezentációban. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | Visszaadja az összes szövegdobozt a megadott dián, amely a megadott szöveget tartalmazza. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | Átalakítja a forrásfájl formátumát a megfelelő [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/)-ra. |
## Lásd még

* Névtér [Aspose::Slides::Util](../)
* Könyvtár [Aspose.Slides](../../)