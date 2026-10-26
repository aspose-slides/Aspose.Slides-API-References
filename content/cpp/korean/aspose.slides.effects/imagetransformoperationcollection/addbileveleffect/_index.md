---
title: AddBiLevelEffect()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 새로운 Bi-Level(흑백) 효과를 컬렉션의 끝에 추가합니다.
type: docs
weight: 144
url: /ko/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) 메서드


새로운 Bi-Level(흑백) 효과를 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | **float** | Bi-Level 효과에 대한 휘도 임계값입니다. 임계값보다 크거나 같은 값은 흰색으로 설정됩니다. 임계값보다 작은 값은 검은색으로 설정됩니다. |

### 반환값

컬렉션에서 새 이미지 효과의 인덱스입니다.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBiLevel](../../ibilevel/)
* 클래스 [ImageTransformOperationCollection](../)
* 네임스페이스 [Aspose::Slides::Effects](../../)
* 라이브러리 [Aspose.Slides](../../../)