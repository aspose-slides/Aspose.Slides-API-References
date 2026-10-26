---
title: FindShape()
second_title: C++용 Aspose.Slides API 레퍼런스
description: PPTX 프레젠테이션에서 대체 텍스트로 모양을 찾습니다.
type: docs
weight: 1
url: /ko/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) method

PPTX 프레젠테이션에서 대체 텍스트로 모양을 찾습니다.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 스캔된 프레젠테이션. |
| altText | [System::String](../../../system/string/) | 모양의 대체 텍스트. |

### 반환 값

[Shape](../../../aspose.slides/shape/) 또는 null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) method

PPTX 프레젠테이션의 슬라이드에서 대체 텍스트로 모양을 찾습니다.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 스캔된 슬라이드. |
| altText | [System::String](../../../system/string/) | 모양의 대체 텍스트. |

### 반환 값

[Shape](../../../aspose.slides/shape/) 또는 null.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../../aspose.slides/ishape/)
* 클래스 [IPresentation](../../../aspose.slides/ipresentation/)
* 클래스 [String](../../../system/string/)
* 클래스 [SlideUtil](../)
* 클래스 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 네임스페이스 [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)