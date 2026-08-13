---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 Summary Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 144
url: /ko/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) 메서드


새로운 Summary Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새로운 Summary Zoom 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새로운 Summary Zoom 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새로운 Summary Zoom 프레임의 너비(포인트 단위). |
| height | **float** | 새로운 Summary Zoom 프레임의 높이(포인트 단위). |

### 반환값

새로 생성된 [ISummaryZoomFrame](../../isummaryzoomframe/).
## 비고


이 메서드는 프레젠테이션의 모든 섹션에 대한 요약 링크를 모아 Summary Zoom 프레임을 생성합니다. 

다음 예제는 컬렉션의 끝에 Summary Zoom 객체를 추가하는 방법을 보여줍니다 (\"Presentation.pptx\" 프레젠테이션에 섹션이 최소 두 개 있다고 가정): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomFrame](../../isummaryzoomframe/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)