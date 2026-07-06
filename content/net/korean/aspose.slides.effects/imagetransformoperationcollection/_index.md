---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes for .NET API 참조
description: 이미지에 적용된 효과 컬렉션을 나타냅니다.
type: docs
weight: 3580
url: /ko/aspose.slides.effects/imagetransformoperationcollection/
---
## ImageTransformOperationCollection 클래스

이미지에 적용된 효과 컬렉션을 나타냅니다.

```csharp
public sealed class ImageTransformOperationCollection : PVIObject, 
    IImageTransformOperationCollection
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 기본 IPresentationComponent 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Count](../../aspose.slides.effects/imagetransformoperationcollection/count) { get; } | 컬렉션에 있는 이미지 효과 수를 반환합니다. 읽기 전용 Int32. |
| [IsReadOnly](../../aspose.slides.effects/imagetransformoperationcollection/isreadonly) { get; } | ICollection이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. 읽기 전용 Boolean. |
| [Item](../../aspose.slides.effects/imagetransformoperationcollection/item) { get; } | 그 인덱스로 컬렉션에서 [`ImageTransformOperation`](../imagetransformoperation)를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.slides.effects/imagetransformoperationcollection/add)(IImageTransformOperation) | 새 이미지 효과를 컬렉션의 끝에 추가합니다. |
| [AddAlphaBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphabileveleffect)(float) | 새 Alpha Bi-Level 효과를 컬렉션의 끝에 추가합니다. |
| [AddAlphaCeilingEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaceilingeffect)() | 새 Alpha Ceiling 효과를 컬렉션의 끝에 추가합니다. |
| [AddAlphaFloorEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaflooreffect)() | 새 Alpha Floor 효과를 컬렉션의 끝에 추가합니다. |
| [AddAlphaInverseEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphainverseeffect)() | 새 Alpha Inverse 효과를 컬렉션의 끝에 추가합니다. |
| [AddAlphaModulateEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulateeffect)() | 새 Alpha Modulate 효과를 컬렉션의 끝에 추가합니다. |
| [AddAlphaModulateFixedEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulatefixedeffect)(float) | 새 Alpha Modulate Fixed 효과를 컬렉션의 끝에 추가합니다. |
| [AddAlphaReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphareplaceeffect)(float) | 새 Alpha Replace 효과를 컬렉션의 끝에 추가합니다. |
| [AddBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbileveleffect)(float) | 새 Bi-Level (흑백) 효과를 컬렉션의 끝에 추가합니다. |
| [AddBlurEffect](../../aspose.slides.effects/imagetransformoperationcollection/addblureffect)(double, bool) | 새 Blur 효과를 컬렉션의 끝에 추가합니다. |
| [AddBrightnessContrastEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbrightnesscontrasteffect)(float, float) | 새 BrightnessContrast 효과를 컬렉션의 끝에 추가합니다. |
| [AddColorChangeEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorchangeeffect)() | 새 Color Change 효과를 컬렉션의 끝에 추가합니다. |
| [AddColorReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorreplaceeffect)() | 새 Color Replacement 효과를 컬렉션의 끝에 추가합니다. |
| [AddDuotoneEffect](../../aspose.slides.effects/imagetransformoperationcollection/addduotoneeffect)() | 새 Duotone 효과를 컬렉션의 끝에 추가합니다. |
| [AddFillOverlayEffect](../../aspose.slides.effects/imagetransformoperationcollection/addfilloverlayeffect)() | 새 Fill Overlay 효과를 컬렉션의 끝에 추가합니다. |
| [AddGrayScaleEffect](../../aspose.slides.effects/imagetransformoperationcollection/addgrayscaleeffect)() | 새 Gray Scale 효과를 컬렉션의 끝에 추가합니다. |
| [AddHSLEffect](../../aspose.slides.effects/imagetransformoperationcollection/addhsleffect)(float, float, float) | 새 Hue/Saturation/Luminance 효과를 컬렉션의 끝에 추가합니다. |
| [AddLuminanceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addluminanceeffect)(float, float) | 새 Luminance 효과를 컬렉션의 끝에 추가합니다. |
| [AddTintEffect](../../aspose.slides.effects/imagetransformoperationcollection/addtinteffect)(float, float) | 새 Tint 효과를 컬렉션의 끝에 추가합니다. |
| [Clear](../../aspose.slides.effects/imagetransformoperationcollection/clear)() | 컬렉션에서 모든 이미지 효과를 제거합니다. |
| [Contains](../../aspose.slides.effects/imagetransformoperationcollection/contains)(IImageTransformOperation) | ICollection에 특정 값이 포함되어 있는지 확인합니다. |
| [CopyTo](../../aspose.slides.effects/imagetransformoperationcollection/copyto)(IImageTransformOperation[], int) | ICollection의 요소들을 지정된 배열 인덱스부터 Array에 복사합니다. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 지정된 객체와 비교합니다. |
| [GetEnumerator](../../aspose.slides.effects/imagetransformoperationcollection/getenumerator)() | 컬렉션을 순회하는 열거자를 반환합니다. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 해시 코드를 반환합니다. |
| [Remove](../../aspose.slides.effects/imagetransformoperationcollection/remove)(IImageTransformOperation) | ICollection에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [RemoveAt](../../aspose.slides.effects/imagetransformoperationcollection/removeat)(int) | 지정된 인덱스에서 컬렉션의 이미지 효과를 제거합니다. |

### 참고

* 클래스 [PVIObject](../../aspose.slides/pviobject)
* 인터페이스 [IImageTransformOperationCollection](../iimagetransformoperationcollection)
* 네임스페이스 [Aspose.Slides.Effects](../../aspose.slides.effects)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->