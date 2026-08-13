---
title: FindShapesByPlaceholderType()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 슬라이드에서 주어진 자리표시자 유형과 일치하는 모든 도형을 검색합니다.
type: docs
weight: 14
url: /ko/aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) 메서드


지정된 슬라이드에서 주어진 자리표시자 유형과 일치하는 모든 도형을 검색합니다.

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 도형을 검색할 슬라이드입니다. |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | 도형을 필터링할 자리표시자 유형입니다. |

### 반환값

지정된 자리표시자 유형과 일치하는 [IShape](../../../aspose.slides/ishape/) 객체 배열입니다.

## 참조

* 열거형 [PlaceholderType](../../../aspose.slides/placeholdertype/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../../aspose.slides/ishape/)
* 클래스 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 클래스 [SlideUtil](../)
* 네임스페이스 [Aspose::Slides::Util](../../)
* 라이브러리 [Aspose.Slides](../../../)