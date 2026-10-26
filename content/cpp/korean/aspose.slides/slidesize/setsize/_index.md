---
title: SetSize()
second_title: Aspose.Slides for C++ API 참조
description: 유형별로 슬라이드 크기를 설정하고 기존 콘텐츠를 스케일링합니다.
type: docs
weight: 53
url: /ko/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) 메서드


슬라이드 크기를 유형별로 설정하고 기존 콘텐츠를 스케일링합니다.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | 적용할 미리 정의된 슬라이드 크기입니다. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 사용할 콘텐츠 스케일링 모드입니다. |
## 비고


[SlideSizeType::Custom](../../slidesizetype/) 이외의 값을 할당하면 선택된 유형에 따라 [SlideSize::get_Size](../get_size/)가 조정되며, [SlideSize::get_Orientation](../get_orientation/)는 유지됩니다. 

## SlideSize::SetSize(float, float, SlideSizeScaleType) 메서드


슬라이드의 치수를 명시적으로 설정하고 기존 콘텐츠를 스케일링합니다.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | **float** | 포인트 단위의 새로운 슬라이드 너비입니다. |
| height | **float** | 포인트 단위의 새로운 슬라이드 높이입니다. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 사용할 콘텐츠 스케일링 모드입니다. |
## 비고


이는 [SlideSize::get_Type](../get_type/) 속성을 [SlideSizeType::Custom](../../slidesizetype/) 로 재설정하고 [Orientation](../../orientation/)를 설정합니다. 

## 참고

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [SlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)