---
title: IImageTransformOperationCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 이미지에 적용된 효과 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iimagetransformoperationcollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

이미지에 적용된 효과 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 컬렉션에서 인덱스로 [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)을 반환합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 컬렉션의 이미지 효과를 제거합니다. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 새 Alpha Bi-Level 효과를 컬렉션 끝에 추가합니다. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 새 Alpha Ceiling 효과를 컬렉션 끝에 추가합니다. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 새 Alpha Floor 효과를 컬렉션 끝에 추가합니다. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 새 Alpha Inverse 효과를 컬렉션 끝에 추가합니다. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 새 Alpha Modulate 효과를 컬렉션 끝에 추가합니다. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 새 Alpha Modulate Fixed 효과를 컬렉션 끝에 추가합니다. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 새 Alpha Replace 효과를 컬렉션 끝에 추가합니다. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 새 Bi-Level (흑백) 효과를 컬렉션 끝에 추가합니다. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 새 Blur 효과를 컬렉션 끝에 추가합니다. |
| [addColorChangeEffect()](#addColorChangeEffect--) | 새 Color Change 효과를 컬렉션 끝에 추가합니다. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 새 Color Replacement 효과를 컬렉션 끝에 추가합니다. |
| [addDuotoneEffect()](#addDuotoneEffect--) | 새 Duotone 효과를 컬렉션 끝에 추가합니다. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 새 Fill Overlay 효과를 컬렉션 끝에 추가합니다. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 새 Gray Scale 효과를 컬렉션 끝에 추가합니다. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 새 Hue/Saturation/Luminance 효과를 컬렉션 끝에 추가합니다. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 새 Luminance 효과를 컬렉션 끝에 추가합니다. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 새 Tint 효과를 컬렉션 끝에 추가합니다. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 새 BrightnessContrast 효과를 컬렉션 끝에 추가합니다. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

컬렉션에서 인덱스로 [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 항목의 인덱스. |

**반환:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 객체.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스에서 컬렉션의 이미지 효과를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제해야 할 이미지 효과의 인덱스. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

새 Alpha Bi-Level 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level 효과의 임계값. |

**반환:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 컬렉션에서 새 이미지 효과의 인덱스.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

새 Alpha Ceiling 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 컬렉션에서 새 이미지 효과의 인덱스.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

새 Alpha Floor 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 컬렉션에서 새 이미지 효과의 인덱스.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

새 Alpha Inverse 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 컬렉션에서 새 이미지 효과의 인덱스.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

새 Alpha Modulate 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 컬렉션에서 새 이미지 효과의 인덱스.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

새 Alpha Modulate Fixed 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| amount | float | 알파를 스케일링할 퍼센트 양. |

**반환:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 컬렉션에서 새 이미지 효과의 인덱스.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

새 Alpha Replace 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alpha | float | 새로운 불투명도 값. |

**반환:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 컬렉션에서 새 이미지 효과의 인덱스.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

새 Bi-Level (흑백) 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| threshold | float | Bi-Level 효과의 밝기 임계값. 임계값 이상은 흰색, 이하는 검정색으로 설정됩니다. |

**반환:**
[IBiLevel](../../com.aspose.slides/ibilevel) - 컬렉션에서 새 이미지 효과의 인덱스.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

새 Blur 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| radius | double | 블러 반경. |
| grow | boolean | 블러링 결과 객체 경계를 확장할지 여부. true이면 경계가 확대되고 false이면 확대되지 않습니다. |

**반환:**
[IBlur](../../com.aspose.slides/iblur) - 컬렉션에서 새 이미지 효과의 인덱스.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

새 Color Change 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IColorChange](../../com.aspose.slides/icolorchange) - 컬렉션에서 새 이미지 효과의 인덱스.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

새 Color Replacement 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 컬렉션에서 새 이미지 효과의 인덱스.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

새 Duotone 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IDuotone](../../com.aspose.slides/iduotone) - 컬렉션에서 새 이미지 효과의 인덱스.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

새 Fill Overlay 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 컬렉션에서 새 이미지 효과의 인덱스.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

새 Gray Scale 효과를 컬렉션 끝에 추가합니다.

**반환:**
[IGrayScale](../../com.aspose.slides/igrayscale) - 컬렉션에서 새 이미지 효과의 인덱스.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

새 Hue/Saturation/Luminance 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hue | float | 색조가 조정되는 각도. |
| saturation | float | 채도가 조정되는 퍼센트. |
| luminance | float | 밝기가 조정되는 퍼센트. |

**반환:**
[IHSL](../../com.aspose.slides/ihsl) - 컬렉션에서 새 이미지 효과의 인덱스.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

새 Luminance 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brightness | float | 밝기를 변경할 퍼센트. |
| contrast | float | 대비를 변경할 퍼센트. |

**반환:**
[ILuminance](../../com.aspose.slides/iluminance) - 컬렉션에서 새 이미지 효과의 인덱스.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

새 Tint 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hue | float | 색조를 틴트할 대상 색조. |
| amount | float | 색상 값이 얼마나 이동하는지 지정합니다. |

**반환:**
[ITint](../../com.aspose.slides/itint) - 컬렉션에서 새 이미지 효과의 인덱스.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

새 BrightnessContrast 효과를 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brightness | float | 밝기를 변경할 퍼센트. |
| contrast | float | 대비를 변경할 퍼센트. |

**반환:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 컬렉션에서 새 이미지 효과의 인덱스.