---
title: SetSize()
second_title: Aspose.Slides for C++ API 참조
description: "슬라이드 크기를 유형에 따라 설정하고 기존 콘텐츠를 스케일링합니다. SlideSizeType::Custom이 아닌 값을 지정하면 선택한 유형에 따라 ISlideSize::get_Size가 조정되며 ISlideSize::get_Orientation이 보존됩니다."
type: docs
weight: 53
url: /ko/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) 메서드

슬라이드 크기를 유형에 따라 설정하고 기존 콘텐츠를 스케일링합니다. [SlideSizeType::Custom](../../slidesizetype/) 이외의 값을 지정하면 선택한 유형에 따라 [ISlideSize::get_Size](../get_size/) 가 조정되며 [ISlideSize::get_Orientation](../get_orientation/) 가 보존됩니다.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | 적용할 미리 정의된 슬라이드 크기. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 사용할 콘텐츠 스케일링 모드. |

## 비고

[SlideSizeType::Custom](../../slidesizetype/) 이외의 값을 지정하면 선택한 유형에 따라 [System::Drawing::Size](../../../system.drawing/size/) 가 조정되며 [Orientation](../../orientation/) 가 보존됩니다.

## ISlideSize::SetSize(float, float, SlideSizeScaleType) 메서드

슬라이드 차원을 명시적으로 설정하고 기존 콘텐츠를 스케일링합니다. 이는 [ISlideSize::get_Type](../get_type/) 값을 [SlideSizeType::Custom](../../slidesizetype/) 로 재설정하고 [ISlideSize::get_Orientation](../get_orientation/) 를 설정합니다.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | **float** | 포인트 단위의 새로운 슬라이드 너비. |
| height | **float** | 포인트 단위의 새로운 슬라이드 높이. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 사용할 콘텐츠 스케일링 모드. |

## 비고

[ISlideSize::get_Type](../get_type/) 속성을 [SlideSizeType::Custom](../../slidesizetype/) 로 재설정하고 [Orientation](../../orientation/) 를 설정합니다.

## 참고

* 열거형 [SlideSizeType](../../slidesizetype/)
* 열거형 [SlideSizeScaleType](../../slidesizescaletype/)
* 클래스 [ISlideSize](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)