---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: 이미지 효과 인스턴스를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

이미지 효과 인스턴스를 생성할 수 있습니다

--------------------

COM 인터페이스용.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Alpha BiLevel 효과를 생성합니다. |
| [createAlphCeiling()](#createAlphCeiling--) | Alpha Ceiling 효과를 생성합니다. |
| [createAlphaFloor()](#createAlphaFloor--) | Alpha floor 효과를 생성합니다. |
| [createAlphaInverse()](#createAlphaInverse--) | Alpha inverse 효과를 생성합니다. |
| [createAlphaModulate()](#createAlphaModulate--) | Alpha modulate 효과를 생성합니다. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Alpha modulate fixed 효과를 생성합니다. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Alpha replace 효과를 생성합니다. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | BiLevel 효과를 생성합니다. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Blur 효과를 생성합니다. |
| [createColorChange()](#createColorChange--) | Color change 효과를 생성합니다. |
| [createColorReplace()](#createColorReplace--) | Color replace 효과를 생성합니다. |
| [createDuotone()](#createDuotone--) | Duotone 효과를 생성합니다. |
| [createFillOverlay()](#createFillOverlay--) | Fill overlay 효과를 생성합니다. |
| [createGrayScale()](#createGrayScale--) | Gray scale 효과를 생성합니다. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Hue Saturation Luminance 효과를 생성합니다. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Luminance 효과를 생성합니다. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tint 효과를 생성합니다. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Alpha BiLevel 효과를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threshold | float | 임계값. |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel 효과.

### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Alpha Ceiling 효과를 생성합니다.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling 효과.

### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Alpha floor 효과를 생성합니다.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor 효과.

### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Alpha inverse 효과를 생성합니다.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst 효과.

### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Alpha modulate 효과를 생성합니다.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate 효과.

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Alpha modulate fixed 효과를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| amount | float | 양. |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed 효과.

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Alpha replace 효과를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | float | Alpha |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace 효과.

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

BiLevel 효과를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threshold | float | 임계값. |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel 효과.

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Blur 효과를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| radius | double | 반경. |
| grow | boolean | 확장 여부. |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - Blur 효과.

### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Color change 효과를 생성합니다.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change 효과.

### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Color replace 효과를 생성합니다.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace 효과.

### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Duotone 효과를 생성합니다.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone 효과.

### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Fill overlay 효과를 생성합니다.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay 효과.

### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Gray scale 효과를 생성합니다.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale 효과를 반환합니다.

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Hue Saturation Luminance 효과를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hue | float | 색조. |
| saturation | float | 채도. |
| luminance | float | 휘도. |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - HSL 효과.

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Luminance 효과를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brightness | float | 밝기. |
| contrast | float | 대비. |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance 효과.

### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Tint 효과를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hue | float | 색조. |
| amount | float | 양. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Tint 효과.