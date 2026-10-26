---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 새 그라데이션 스톱을 생성하고 컬렉션 끝에 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/igradientstopcollection/add/
---
## IGradientStopCollection::Add(float, System::Drawing::Color) 메서드

새 그라데이션 스톱을 만들고 컬렉션 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, System::Drawing::Color color)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | **float** | 새 그라데이션 스톱의 위치. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | 새 그라데이션 스톱의 색상. |

### Return Value

컬렉션에서 새 그라데이션 스톱의 인덱스.

## IGradientStopCollection::Add(float, PresetColor) 메서드

새 그라데이션 스톱을 만들고 컬렉션 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, PresetColor presetColor)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | **float** | 새 그라데이션 스톱의 위치. |
| presetColor | [PresetColor](../../presetcolor/) | 새 그라데이션 스톱의 색상. |

### Return Value

컬렉션에서 새 그라데이션 스톱의 인덱스.

## IGradientStopCollection::Add(float, SchemeColor) 메서드

새 그라데이션 스톱을 만들고 컬렉션 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, SchemeColor schemeColor)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | **float** | 새 그라데이션 스톱의 위치. |
| schemeColor | [SchemeColor](../../schemecolor/) | 새 그라데이션 스톱의 색상. |

### Return Value

컬렉션에서 새 그라데이션 스톱의 인덱스.

## See Also

* 열거형 [PresetColor](../../presetcolor/)
* 열거형 [SchemeColor](../../schemecolor/)
* 형식 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGradientStop](../../igradientstop/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [IGradientStopCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)