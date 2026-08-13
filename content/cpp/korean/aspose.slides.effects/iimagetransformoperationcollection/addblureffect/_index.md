---
title: AddBlurEffect()
second_title: Aspose.Slides for C++ API 참조
description: 새로운 Blur 효과를 컬렉션 끝에 추가합니다.
type: docs
weight: 131
url: /ko/aspose.slides.effects/iimagetransformoperationcollection/addblureffect/
---
## IImageTransformOperationCollection::AddBlurEffect(double, bool) method


새로운 [Blur](../../blur/) 효과를 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IBlur> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBlurEffect(double radius, bool grow)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| radius | **double** | 블러의 반경. |
| grow | **bool** | 블러링 결과 객체의 경계가 확대되는지 여부를 지정합니다. True는 경계가 확대됨을 나타내고 false는 그렇지 않음을 나타냅니다. |

### 반환 값

컬렉션에서 새로운 이미지 효과의 인덱스.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBlur](../../iblur/)
* 클래스 [IImageTransformOperationCollection](../)
* 네임스페이스 [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)