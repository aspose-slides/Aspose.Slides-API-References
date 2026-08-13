---
title: get_InkEffectImages()
second_title: Aspose.Slides for C++ API 참조
description: 잉크 브러시의 시각 효과를 시뮬레이션하기 위해 사용되는 사용자 정의 이미지 컬렉션을 가져옵니다. 이러한 이미지는 Galaxy, Rainbow 등과 같은 특정 InkEffectType 값을 사용하여 잉크를 렌더링할 때 사용됩니다. 직접 이미지를 제공함으로써 각 잉크 효과가 표시되는 방식을 제어할 수 있습니다.
type: docs
weight: 14
url: /ko/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() 메서드

잉크 브러시의 시각 효과를 시뮬레이션하기 위해 사용되는 사용자 정의 이미지 컬렉션을 가져옵니다. 이러한 이미지는 Galaxy, Rainbow 등과 같은 특정 [InkEffectType](../../inkeffecttype/) 값을 사용하여 잉크를 렌더링할 때 사용됩니다. 자체 이미지를 제공함으로써 각 잉크 효과가 표시되는 방식을 제어할 수 있습니다.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## 비고

이 속성은 기본 잉크 효과 텍스처를 사용자 정의 텍스처로 교체할 수 있게 하며, 기본 자산이 라이선스 제한을 받거나 런타임에 사용할 수 없을 때 특히 유용합니다.

사전의 각 항목은 [InkEffectType](../../inkeffecttype/) 값을 해당 [IImage](../../../aspose.slides/iimage/) 개체(예: Bitmap 또는 **Aspose** 이미지 인터페이스)와 연결해야 합니다.

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## 참조

* 열거형 [InkEffectType](../../inkeffecttype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDictionary](../../../system.collections.generic/idictionary/)
* 클래스 [IImage](../../../aspose.slides/iimage/)
* 클래스 [Ink](../)
* 네임스페이스 [Aspose::Slides::Ink](../../)
* 라이브러리 [Aspose.Slides](../../../)