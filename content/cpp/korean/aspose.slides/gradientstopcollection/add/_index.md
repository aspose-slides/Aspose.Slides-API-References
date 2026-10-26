---
title: Add()
second_title: Aspose.Slides C++ API 레퍼런스
description: 새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) 메서드

새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```

### 매개변수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| position | **float** | 새 그라디언트 스톱의 위치. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | 새 그라디언트 스톱의 색상. |

### 반환값

컬렉션에서 새 그라디언트 스톱의 인덱스.

## GradientStopCollection::Add(float, PresetColor) 메서드

새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```

### 매개변수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| position | **float** | 새 그라디언트 스톱의 위치. |
| presetColor | [PresetColor](../../presetcolor/) | 새 그라디언트 스톱의 색상. |

### 반환값

컬렉션에서 새 그라디언트 스톱의 인덱스.

## GradientStopCollection::Add(float, SchemeColor) 메서드

새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```

### 매개변수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| position | **float** | 새 그라디언트 스톱의 위치. |
| schemeColor | [SchemeColor](../../schemecolor/) | 새 그라디언트 스톱의 색상. |

### 반환값

컬렉션에서 새 그라디언트 스톱의 인덱스.

## 참조

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGradientStop](../../igradientstop/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [GradientStopCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)