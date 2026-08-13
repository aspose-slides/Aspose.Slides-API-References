---
title: AddHSLEffect()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션 끝에 새로운 Hue/Saturation/Luminance 효과를 추가합니다.
type: docs
weight: 209
url: /ko/aspose.slides.effects/iimagetransformoperationcollection/addhsleffect/
---
## IImageTransformOperationCollection::AddHSLEffect(float, float, float) 메서드

새로운 Hue/Saturation/Luminance 효과를 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IHSL> Aspose::Slides::Effects::IImageTransformOperationCollection::AddHSLEffect(float hue, float saturation, float luminance)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hue | **float** | 색조가 조정되는 각도 수. |
| saturation | **float** | 포화도가 조정되는 비율. |
| luminance | **float** | 휘도가 조정되는 비율. |

### 반환값

컬렉션에서 새 이미지 효과의 인덱스.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IHSL](../../ihsl/)
* 클래스 [IImageTransformOperationCollection](../)
* 네임스페이스 [Aspose::Slides::Effects](../../)
* 라이브러리 [Aspose.Slides](../../../)