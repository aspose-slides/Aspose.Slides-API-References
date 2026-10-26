---
title: InsertSummaryZoomFrame()
second_title: C++용 Aspose.Slides API 참조
description: 새 Summary Zoom 프레임을 생성하고 지정된 인덱스에 shape collection에 삽입합니다.
type: docs
weight: 170
url: /ko/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) 메서드

새 Summary Zoom 프레임을 만들고 지정된 인덱스에 shape collection에 삽입합니다.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 요약 Summary Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | **float** | 새 Summary Zoom 프레임의 x좌표(포인트 단위). |
| y | **float** | 새 Summary Zoom 프레임의 y좌표(포인트 단위). |
| width | **float** | 새 Summary Zoom 프레임의 너비(포인트 단위). |
| height | **float** | 새 Summary Zoom 프레임의 높이(포인트 단위). |

### 반환값

새로 생성된 [ISummaryZoomFrame](../../isummaryzoomframe/).

## 비고

이 메서드는 프레젠테이션의 모든 섹션에 대한 요약 링크를 집계하는 Summary Zoom 프레임을 생성합니다.

이 예제는 컬렉션의 지정된 인덱스에 Summary Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다(예: "Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 있다고 가정):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)