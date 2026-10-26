---
title: AddBiLevelEffect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 Bi-Level(흑백) 효과를 컬렉션의 끝에 추가합니다.
type: docs
weight: 118
url: /ko/aspose.slides.effects/iimagetransformoperationcollection/addbileveleffect/
---
## IImageTransformOperationCollection::AddBiLevelEffect(float) 메서드


새로운 Bi-Level(흑백) 효과를 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IBiLevel> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBiLevelEffect(float threshold)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | **float** | Bi-Level 효과에 대한 광도 임계값. 임계값보다 크거나 같은 값은 흰색으로 설정됩니다. 임계값보다 작은 값은 검은색으로 설정됩니다. |

### 반환 값

컬렉션에서 새로운 이미지 효과의 인덱스.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBiLevel](../../ibilevel/)
* Class [IImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)