---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes for .NET API 참조
description: Microsoft PowerPoint 프레젠테이션에서 다양한 효과를 작업하기 위한 클래스를 포함합니다.
type: docs
weight: 60
url: /ko/aspose.slides.effects/
---
Microsoft PowerPoint 프레젠테이션에서 다양한 효과를 작업하기 위한 클래스를 포함합니다.

## Classes

| 클래스 | 설명 |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Alpha Bi-Level 효과를 나타냅니다. Alpha (Opacity) 값이 임계값보다 작으면 0(완전 투명)으로, 임계값 이상이면 100%(완전 불투명)으로 변경됩니다. |
| [AlphaCeiling](./alphaceiling) | Alpha Ceiling 효과를 나타냅니다. Alpha (opacity) 값이 0보다 크면 100%로 변경됩니다. 즉, 부분적으로 불투명한 것이 완전히 불투명해집니다. |
| [AlphaFloor](./alphafloor) | Alpha Floor 효과를 나타냅니다. Alpha (opacity) 값이 100%보다 작으면 0으로 변경됩니다. 즉, 부분적으로 투명한 것이 완전히 투명해집니다. |
| [AlphaInverse](./alphainverse) | Alpha Inverse 효과를 나타냅니다. Alpha (opacity) 값이 100%에서 빼서 반전됩니다. |
| [AlphaModulate](./alphamodulate) | Alpha Modulate 효과를 나타냅니다. 효과 Alpha (opacity) 값에 고정 비율을 곱합니다. 효과 컨테이너는 조절할 Alpha 값을 포함하는 효과를 지정합니다. |
| [AlphaModulateFixed](./alphamodulatefixed) | Alpha Modulate Fixed 효과를 나타냅니다. 효과 Alpha (opacity) 값에 고정 비율을 곱합니다. |
| [AlphaReplace](./alphareplace) | Alpha Replace 효과를 나타냅니다. 효과 Alpha (opacity) 값이 고정 Alpha 로 교체됩니다. |
| [BiLevel](./bilevel) | Bi-Level(흑백) 효과를 나타냅니다. 입력 색상의 휘도가 지정된 임계값보다 작으면 검정으로, 임계값 이상이면 흰색으로 변경됩니다. Alpha 효과 값은 영향을 받지 않습니다. |
| [Blur](./blur) | 전체 도형에 적용되는 Blur 효과를 나타냅니다. 채우기를 포함한 모든 색상 채널, Alpha 포함이 영향을 받습니다. |
| [BrightnessContrast](./brightnesscontrast) | BrightnessContrast 효과를 나타냅니다. 밝기와 대비를 조정합니다. |
| [ColorChange](./colorchange) | Color Change 효과를 나타냅니다. FromColor 인스턴스가 ToColor 인스턴스로 교체됩니다. |
| [ColorReplace](./colorreplace) | Color Replacement 효과를 나타냅니다. 모든 효과 색상이 고정 색상으로 변경됩니다. Alpha 값은 영향을 받지 않습니다. |
| [Duotone](./duotone) | Duotone 효과를 나타냅니다. 각 픽셀마다 Color1과 Color2를 선형 보간하여 새로운 색상을 결정합니다. |
| [EffectFactory](./effectfactory) | 효과를 생성할 수 있습니다. |
| [FillOverlay](./filloverlay) | Fill Overlay 효과를 나타냅니다. Fill overlay는 객체에 추가 채우기를 지정하고 두 채우기를 혼합하는 데 사용할 수 있습니다. |
| [Glow](./glow) | Glow 효과를 나타냅니다. 색상이 흐려진 외곽선이 객체 가장자리 밖에 추가됩니다. |
| [GrayScale](./grayscale) | Gray Scale 효과를 나타냅니다. 모든 효과 색상 값을 그 휘도에 해당하는 회색 음영으로 변환합니다. 효과 Alpha (opacity) 값은 영향을 받지 않습니다. |
| [HSL](./hsl) | Hue/Saturation/Luminance 효과를 나타냅니다. 색조, 채도, 휘도를 각각 현재 값에 따라 조정할 수 있습니다. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | 읽기 전용 컬렉션의 이미지 변환 효과를 나타내는 불변 객체입니다. |
| [ImageTransformOperation](./imagetransformoperation) | 추상 이미지 변환 효과를 나타냅니다. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | 이미지에 적용되는 효과 컬렉션을 나타냅니다. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | 이미지 변환 작업을 생성할 수 있습니다. |
| [InnerShadow](./innershadow) | Inner Shadow 효과를 나타냅니다. |
| [Luminance](./luminance) | Luminance 효과를 나타냅니다. 밝기가 선형으로 모든 색을 흰색 또는 검정색에 가깝게 이동시키고, 대비가 색들을 더 가깝게 혹은 멀게 스케일합니다. |
| [OuterShadow](./outershadow) | Outer Shadow 효과를 나타냅니다. |
| [PresetShadow](./presetshadow) | Preset Shadow 효과를 나타냅니다. |
| [Reflection](./reflection) | Reflection 효과를 나타냅니다. |
| [SoftEdge](./softedge) | 부드러운 가장자 효과를 나타냅니다. 도형의 가장자리는 흐려지지만 채우기는 영향을 받지 않습니다. |
| [Tint](./tint) | Tint 효과를 나타냅니다. 지정된 양만큼 색조를 향하거나 멀어지도록 효과 색상 값을 이동시킵니다. |

## Interfaces

| 인터페이스 | 설명 |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Alpha Bi-Level 효과를 나타냅니다. Alpha (Opacity) 값이 임계값보다 작으면 0(완전 투명)으로, 임계값 이상이면 100%(완전 불투명)으로 변경됩니다. |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Alpha Bi-Level 효과를 나타내는 불변 객체입니다. Alpha (Opacity) 값이 임계값보다 작으면 0(완전 투명)으로, 임계값 이상이면 100%(완전 불투명)으로 변경됩니다. |
| [IAlphaCeiling](./ialphaceiling) | Alpha Ceiling 효과를 나타냅니다. Alpha (opacity) 값이 0보다 크면 100%로 변경됩니다. 즉, 부분적으로 불투명한 것이 완전히 불투명해집니다. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Alpha Ceiling 효과를 나타내는 불변 객체입니다. Alpha (opacity) 값이 0보다 크면 100%로 변경됩니다. 즉, 부분적으로 불투명한 것이 완전히 불투명해집니다. |
| [IAlphaFloor](./ialphafloor) | Alpha Floor 효과를 나타냅니다. Alpha (opacity) 값이 100%보다 작으면 0으로 변경됩니다. 즉, 부분적으로 투명한 것이 완전히 투명해집니다. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Alpha Floor 효과를 나타내는 불변 객체입니다. Alpha (opacity) 값이 100%보다 작으면 0으로 변경됩니다. 즉, 부분적으로 투명한 것이 완전히 투명해집니다. |
| [IAlphaInverse](./ialphainverse) | Alpha Inverse 효과를 나타냅니다. Alpha (opacity) 값이 100%에서 빼서 반전됩니다. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Alpha Inverse 효과를 나타내는 불변 객체입니다. Alpha (opacity) 값이 100%에서 빼서 반전됩니다. |
| [IAlphaModulate](./ialphamodulate) | Alpha Modulate 효과를 나타냅니다. 효과 Alpha (opacity) 값에 고정 비율을 곱합니다. 효과 컨테이너는 조절할 Alpha 값을 포함하는 효과를 지정합니다. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Alpha Modulate 효과를 나타내는 불변 객체입니다. 효과 Alpha (opacity) 값에 고정 비율을 곱합니다. 효과 컨테이너는 조절할 Alpha 값을 포함하는 효과를 지정합니다. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Alpha Modulate Fixed 효과를 나타냅니다. 효과 Alpha (opacity) 값에 고정 비율을 곱합니다. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Alpha Modulate Fixed 효과를 나타내는 불변 객체입니다. 효과 Alpha (opacity) 값에 고정 비율을 곱합니다. |
| [IAlphaReplace](./ialphareplace) | 기본 IImageTransformOperation 인터페이스를 나타냅니다. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Alpha Replace 효과를 나타내는 불변 객체입니다. 효과 Alpha (opacity) 값이 고정 Alpha 로 교체됩니다. |
| [IBiLevel](./ibilevel) | 기본 IImageTransformOperation 인터페이스를 나타냅니다. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Bi-Level(흑백) 효과를 나타내는 불변 객체입니다. 입력 색상의 휘도가 지정된 임계값보다 작으면 검정으로, 임계값 이상이면 흰색으로 변경됩니다. Alpha 효과 값은 영향을 받지 않습니다. |
| [IBlur](./iblur) | 전체 도형에 적용되는 Blur 효과를 나타냅니다. 채우기를 포함한 모든 색상 채널, Alpha 포함이 영향을 받습니다. |
| [IBlurEffectiveData](./iblureffectivedata) | 전체 도형에 적용되는 Blur 효과를 나타내는 불변 객체입니다. 모든 색상 채널, Alpha 포함이 영향을 받습니다. |
| [IBrightnessContrast](./ibrightnesscontrast) | BrightnessContrast 효과를 나타냅니다. 밝기와 대비를 조정합니다. |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | BrightnessContrast 효과를 나타내는 불변 객체입니다. 밝기와 대비를 조정합니다. |
| [IColorChange](./icolorchange) | Color Change 효과를 나타냅니다. FromColor 인스턴스가 ToColor 인스턴스로 교체됩니다. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Color Change 효과를 나타내는 불변 객체입니다. FromColor 인스턴스가 ToColor 인스턴스로 교체됩니다. |
| [IColorReplace](./icolorreplace) | Color Replacement 효과를 나타냅니다. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Color Replacement 효과를 나타내는 불변 객체입니다. 모든 효과 색상이 고정 색상으로 변경되고 Alpha 값은 영향을 받지 않습니다. |
| [IDuotone](./iduotone) | Duotone 효과를 나타냅니다. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Duotone 효과를 나타내는 불변 객체입니다. 각 픽셀마다 clr1과 clr2를 선형 보간하여 새로운 색을 결정합니다. |
| [IEffectEffectiveData](./ieffecteffectivedata) | 효과를 나타내는 불변 객체의 기반 클래스입니다. |
| [IEffectFactory](./ieffectfactory) | 효과 인스턴스를 생성할 수 있습니다. |
| [IFillOverlay](./ifilloverlay) | Fill Overlay 효과를 나타냅니다. Fill overlay는 객체에 추가 채우기를 지정하고 두 채우기를 혼합하는 데 사용할 수 있습니다. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Fill Overlay 효과를 나타내는 불변 객체입니다. Fill overlay는 객체에 추가 채우기를 지정하고 두 채우기를 혼합하는 데 사용할 수 있습니다. |
| [IGlow](./iglow) | Glow 효과를 나타냅니다. 색상이 흐려진 외곽선이 객체 가장자리 밖에 추가됩니다. |
| [IGlowEffectiveData](./igloweffectivedata) | Glow 효과를 나타내는 불변 객체입니다. 색상이 흐려진 외곽선이 객체 가장자리 밖에 추가됩니다. |
| [IGrayScale](./igrayscale) | IImageTransformOperation 인터페이스를 나타냅니다. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Gray Scale 효과를 나타냅니다. 모든 효과 색상 값을 그 휘도에 해당하는 회색 음영으로 변환합니다. 효과 Alpha (opacity) 값은 영향을 받지 않습니다. |
| [IHSL](./ihsl) | Hue/Saturation/Luminance 효과를 나타냅니다. 색조, 채도, 휘도를 각각 현재 값에 따라 조정할 수 있습니다. |
| [IHSLEffectiveData](./ihsleffectivedata) | Hue/Saturation/Luminance 효과를 나타냅니다. 색조, 채도, 휘도를 각각 현재 값에 따라 조정할 수 있습니다. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | 읽기 전용 이미지 변환 효과 컬렉션을 나타내는 불변 객체입니다. |
| [IImageTransformOperation](./iimagetransformoperation) | 추상 이미지 변환 효과를 나타냅니다. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | 이미지에 적용되는 효과 컬렉션을 나타냅니다. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | 이미지 효과 인스턴스를 생성할 수 있습니다. |
| [IInnerShadow](./iinnershadow) | Inner Shadow 효과를 나타냅니다. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Inner Shadow 효과를 나타내는 불변 객체입니다. |
| [ILuminance](./iluminance) | Luminance 효과를 나타냅니다. 밝기가 선형으로 모든 색을 흰색 또는 검정색에 가깝게 이동시키고, 대비가 색들을 더 가깝게 혹은 멀게 스케일합니다. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Luminance 효과를 나타냅니다. 밝기가 선형으로 모든 색을 흰색 또는 검정색에 가깝게 이동시키고, 대비가 색들을 더 가깝게 혹은 멀게 스케일합니다. |
| [IOuterShadow](./ioutershadow) | Outer Shadow 효과를 나타냅니다. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Outer Shadow 효과를 나타내는 불변 객체입니다. |
| [IPresetShadow](./ipresetshadow) | Preset Shadow 효과를 나타냅니다. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Preset Shadow 효과를 나타내는 불변 객체입니다. |
| [IReflection](./ireflection) | Reflection 효과를 나타냅니다. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Reflection 효과를 나타내는 불변 객체입니다. |
| [ISoftEdge](./isoftedge) | Soft Edge 효과를 나타냅니다. 도형의 가장자리는 흐려지지만 채우기는 영향을 받지 않습니다. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Soft Edge 효과를 나타내는 불변 객체입니다. 도형의 가장자리는 흐려지지만 채우기는 영향을 받지 않습니다. |
| [ITint](./itint) | Tint 효과를 나타냅니다. 지정된 양만큼 색조를 향하거나 멀어지도록 효과 색상 값을 이동시킵니다. |
| [ITintEffectiveData](./itinteffectivedata) | Tint 효과를 나타내는 불변 객체입니다. 지정된 양만큼 색조를 향하거나 멀어지도록 효과 색상 값을 이동시킵니다. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->