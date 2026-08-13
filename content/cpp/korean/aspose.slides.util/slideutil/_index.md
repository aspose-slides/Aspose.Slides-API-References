---
title: SlideUtil
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션에서 도형과 텍스트를 검색하는데 도움이 되는 메서드를 제공합니다.
type: docs
weight: 14
url: /ko/aspose.slides.util/slideutil/
---
## SlideUtil 클래스

프레젠테이션에서 도형과 텍스트를 검색하는 데 도움이 되는 메서드를 제공합니다.

```cpp
class SlideUtil
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | 슬라이드의 모든 도형 배치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | 슬라이드의 모든 도형 배치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | 슬라이드의 모든 도형 배치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | 슬라이드의 모든 도형 배치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | 프레젠테이션에서 텍스트를 찾아 주어진 형식으로 교체합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | PPTX 프레젠테이션에서 대체 텍스트로 도형을 찾습니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | PPTX 프레젠테이션의 슬라이드에서 대체 텍스트로 도형을 찾습니다. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | 지정된 슬라이드에서 주어진 자리표시자 유형과 일치하는 모든 도형을 검색합니다. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | PPTX 프레젠테이션의 슬라이드에 있는 모든 텍스트 프레임을 반환합니다. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | PPTX 프레젠테이션의 모든 텍스트 프레임을 반환합니다. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | 지정된 슬라이드에서 주어진 텍스트를 포함하는 모든 텍스트 프레임을 반환합니다. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | 소스 파일 형식을 해당 [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/)(으)로 변환합니다. |
## 참고

* 네임스페이스 [Aspose::Slides::Util](../)
* 라이브러리 [Aspose.Slides](../../)