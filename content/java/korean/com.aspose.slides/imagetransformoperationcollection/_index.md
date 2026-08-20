---
title: ImageTransformOperationCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 이미지에 적용된 효과들의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imagetransformoperationcollection/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

이미지에 적용된 효과 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | 컬렉션에서 인덱스로 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)을 반환합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 이미지 효과를 제거합니다. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 컬렉션 끝에 새로운 Alpha Bi-Level 효과를 추가합니다. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 컬렉션 끝에 새로운 Alpha Ceiling 효과를 추가합니다. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 컬렉션 끝에 새로운 Alpha Floor 효과를 추가합니다. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 컬렉션 끝에 새로운 Alpha Inverse 효과를 추가합니다. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 컬렉션 끝에 새로운 Alpha Modulate 효과를 추가합니다. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 컬렉션 끝에 새로운 Alpha Modulate Fixed 효과를 추가합니다. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 컬렉션 끝에 새로운 Alpha Replace 효과를 추가합니다. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 컬렉션 끝에 새로운 Bi-Level (흑백) 효과를 추가합니다. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 컬렉션 끝에 새로운 Blur 효과를 추가합니다. |
| [addColorChangeEffect()](#addColorChangeEffect--) | 컬렉션 끝에 새로운 Color Change 효과를 추가합니다. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 컬렉션 끝에 새로운 Color Replacement 효과를 추가합니다. |
| [addDuotoneEffect()](#addDuotoneEffect--) | 컬렉션 끝에 새로운 Duotone 효과를 추가합니다. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 컬렉션 끝에 새로운 Fill Overlay 효과를 추가합니다. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 컬렉션 끝에 새로운 Gray Scale 효과를 추가합니다. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 컬렉션 끝에 새로운 Hue/Saturation/Luminance 효과를 추가합니다. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 컬렉션 끝에 새로운 Luminance 효과를 추가합니다. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 컬렉션 끝에 새로운 Tint 효과를 추가합니다. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 컬렉션 끝에 새로운 BrightnessContrast 효과를 추가합니다. |
| [size()](#size--) | 컬렉션에 이미지 효과의 수를 반환합니다. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | 컬렉션 끝에 새로운 이미지 효과를 추가합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 이미지 효과를 제거합니다. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 지정된 배열 인덱스부터 배열에 복사합니다. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 항목을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

컬렉션에서 인덱스로 [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)을 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환값:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 객체.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 이미지 효과를 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 삭제해야 할 이미지 효과의 인덱스. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

컬렉션 끝에 새로운 Alpha Bi-Level 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| threshold | float | 알파 바이레벨 효과의 임계값. |

**반환값:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

컬렉션 끝에 새로운 Alpha Ceiling 효과를 추가합니다.

**반환값:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

컬렉션 끝에 새로운 Alpha Floor 효과를 추가합니다.

**반환값:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

컬렉션 끝에 새로운 Alpha Inverse 효과를 추가합니다.

**반환값:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

컬렉션 끝에 새로운 Alpha Modulate 효과를 추가합니다.

**반환값:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

컬렉션 끝에 새로운 Alpha Modulate Fixed 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| amount | float | 알파를 스케일링할 퍼센트 값. |

**반환값:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

컬렉션 끝에 새로운 Alpha Replace 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| alpha | float | 새로운 불투명도 값. |

**반환값:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

컬렉션 끝에 새로운 Bi-Level (흑백) 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| threshold | float | Bi-Level 효과의 밝기 임계값. 임계값 이상은 흰색으로, 이하는 검은색으로 설정됩니다. |

**반환값:**
[IBiLevel](../../com.aspose.slides/ibilevel) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

컬렉션 끝에 새로운 Blur 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| radius | double | 블러 반경. |
| grow | boolean | 블러링 결과 객체 경계가 확장되는지 지정합니다. true이면 경계가 확장되고 false이면 확장되지 않습니다. |

**반환값:**
[IBlur](../../com.aspose.slides/iblur) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

컬렉션 끝에 새로운 Color Change 효과를 추가합니다.

**반환값:**
[IColorChange](../../com.aspose.slides/icolorchange) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

컬렉션 끝에 새로운 Color Replacement 효과를 추가합니다.

**반환값:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

컬렉션 끝에 새로운 Duotone 효과를 추가합니다.

**반환값:**
[IDuotone](../../com.aspose.slides/iduotone) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

컬렉션 끝에 새로운 Fill Overlay 효과를 추가합니다.

**반환값:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

컬렉션 끝에 새로운 Gray Scale 효과를 추가합니다.

**반환값:**
[IGrayScale](../../com.aspose.slides/igrayscale) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

컬렉션 끝에 새로운 Hue/Saturation/Luminance 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| hue | float | 색조가 조정되는 각도 수. |
| saturation | float | 채도가 조정되는 백분율. |
| luminance | float | 밝기가 조정되는 백분율. |

**반환값:**
[IHSL](../../com.aspose.slides/ihsl) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

컬렉션 끝에 새로운 Luminance 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| brightness | float | 밝기를 변경할 비율. |
| contrast | float | 대비를 변경할 비율. |

**반환값:**
[ILuminance](../../com.aspose.slides/iluminance) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

컬렉션 끝에 새로운 Tint 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| hue | float | 색조를 tint 할 대상. |
| amount | float | 색상 값이 얼마나 이동되는지 지정합니다. |

**반환값:**
[ITint](../../com.aspose.slides/itint) - 컬렉션에 새로운 이미지 효과의 인덱스.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

컬렉션 끝에 새로운 BrightnessContrast 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| brightness | float | 밝기를 변경할 비율. |
| contrast | float | 대비를 변경할 비율. |

**반환값:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 컬렉션에 새로운 이미지 효과의 인덱스.

### size() {#size--}
```
public final int size()
```

컬렉션에 이미지 효과의 수를 반환합니다. 읽기 전용 int.

**반환값:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용이면 true, 그렇지 않으면 false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

컬렉션 끝에 새로운 이미지 효과를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 컬렉션 끝에 추가할 이미지 효과. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 이미지 효과를 제거합니다.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 객체. |

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에 item이 있으면 true, 그렇지 않으면 false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 지정된 배열 인덱스부터 배열에 복사합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | 복사된 요소의 대상이 되는 1차원 배열. [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 복사됩니다. 배열은 0 기반 인덱싱이어야 합니다. |
| arrayIndex | int | 복사를 시작할 배열의 0 기반 인덱스. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 항목을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 제거할 객체. |

**반환값:**
boolean - item이 [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 성공적으로 제거되면 true, 그렇지 않으면 false. 이 메서드는 원본 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 item이 없을 경우에도 false를 반환합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 컬렉션을 순회할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 전체 컬렉션에 대한 java.util.Iterator.