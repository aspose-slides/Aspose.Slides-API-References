---
title: GetAllTextFrames()
second_title: Aspose.Slides for C++ API 레퍼런스
description: PPTX 프레젠테이션의 모든 텍스트 프레임을 반환합니다.
type: docs
weight: 79
url: /ko/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) 메서드

PPTX 프레젠테이션의 모든 텍스트 프레임을 반환합니다.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 스캔된 프레젠테이션. |
| withMasters | **bool** | 마스터 슬라이드를 스캔할지 여부를 결정합니다. |

### 반환값

[TextFrame](../../../aspose.slides/textframe/) 객체 배열.

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITextFrame](../../../aspose.slides/itextframe/)
* 클래스 [IPresentation](../../../aspose.slides/ipresentation/)
* 클래스 [SlideUtil](../)
* 네임스페이스 [Aspose::Slides::Util](../../)
* 라이브러리 [Aspose.Slides](../../../)