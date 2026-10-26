---
title: AddBlurEffect()
second_title: Aspose.Slides C++ API 참조
description: 컬렉션의 끝에 새로운 Blur 효과를 추가합니다.
type: docs
weight: 157
url: /ko/aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) 메서드

새로운 [Blur](../../blur/) 효과를 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| radius | **double** | 블러의 반경. |
| grow | **bool** | 블러링 결과 객체의 경계가 확대되어야 하는지를 지정합니다. True는 경계가 확대됨을 나타내고 false는 그렇지 않음을 나타냅니다. |

### 반환 값

컬렉션에서 새 이미지 효과의 인덱스.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBlur](../../iblur/)
* 클래스 [ImageTransformOperationCollection](../)
* 네임스페이스 [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)