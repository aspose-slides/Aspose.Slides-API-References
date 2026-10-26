---
title: SlideUtil
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Udostępnia metody, które pomagają wyszukiwać kształty i tekst w prezentacji.
type: docs
weight: 14
url: /pl/aspose.slides.util/slideutil/
---
## SlideUtil klasa

Udostępnia metody, które pomagają wyszukiwać kształty i tekst w prezentacji.

```cpp
class SlideUtil
```

## Metody

| Metoda | Opis |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Zmienia rozmieszczenie wszystkich kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Zmienia rozmieszczenie wybranych kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | Zmienia rozmieszczenie wszystkich kształtów w grupie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Zmienia rozmieszczenie wybranych kształtów w grupie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | Znajduje i zamienia tekst w prezentacji przy użyciu podanego formatu |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | Znajduje kształt po alternatywnym tekście w prezentacji PPTX. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | Znajduje kształt po alternatywnym tekście na slajdzie w prezentacji PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | Wyszukuje wszystkie kształty na określonym slajdzie, które pasują do podanego typu zastępnika. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Zwraca wszystkie ramki tekstowe na slajdzie w prezentacji PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | Zwraca wszystkie ramki tekstowe w prezentacji PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | Zwraca wszystkie ramki tekstowe na określonym slajdzie, które zawierają podany tekst. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | Konwertuje format pliku źródłowego do odpowiadającego [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/). |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Util](../)
* Biblioteka [Aspose.Slides](../../)