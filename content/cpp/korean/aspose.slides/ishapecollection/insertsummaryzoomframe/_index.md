---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 Summary Zoom 프레임을 생성하고 지정된 인덱스에 shape collection에 삽입합니다.
type: docs
weight: 157
url: /ko/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) 메서드

새 Summary Zoom 프레임을 생성하고 지정된 인덱스에 shape collection에 삽입합니다.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | Summary Zoom 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 Summary Zoom 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 Summary Zoom 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 Summary Zoom 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 Summary Zoom 프레임의 높이(포인트 단위)입니다. |

### 반환 값

새로 생성된 [ISummaryZoomFrame](../../isummaryzoomframe/).

## 비고

이 메서드는 프레젠테이션의 모든 섹션에 대한 summary 링크를 집계하는 Summary Zoom 프레임을 생성합니다.

이 예제는 컬렉션의 지정된 인덱스에 Summary Zoom 객체를 생성하고 삽입하는 방법을 보여 줍니다(예: \"Presentation.pptx\" 프레젠테이션에 섹션이 두 개 이상 있다고 가정). 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)