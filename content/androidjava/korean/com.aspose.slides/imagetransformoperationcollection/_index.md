---
title: ImageTransformOperationCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 이미지는 적용되는 효과의 컬렉션을 나타냅니다.
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

이미지에 적용되는 효과 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)를 컬렉션에서 인덱스로 반환합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 컬렉션의 이미지 효과를 제거합니다. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 새 Alpha Bi-Level 효과를 컬렉션의 끝에 추가합니다. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 새 Alpha Ceiling 효과를 컬렉션의 끝에 추가합니다. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 새 Alpha Floor 효과를 컬렉션의 끝에 추가합니다. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 새 Alpha Inverse 효과를 컬렉션의 끝에 추가합니다. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 새 Alpha Modulate 효과를 컬렉션의 끝에 추가합니다. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 새 Alpha Modulate Fixed 효과를 컬렉션의 끝에 추가합니다. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 새 Alpha Replace 효과를 컬렉션의 끝에 추가합니다. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 새 Bi-Level(흑백) 효과를 컬렉션의 끝에 추가합니다. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 새 Blur 효과를 컬렉션의 끝에 추가합니다. |
| [addColorChangeEffect()](#addColorChangeEffect--) | 새 Color Change 효과를 컬렉션의 끝에 추가합니다. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 새 Color Replacement 효과를 컬렉션의 끝에 추가합니다. |
| [addDuotoneEffect()](#addDuotoneEffect--) | 새 Duotone 효과를 컬렉션의 끝에 추가합니다. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 새 Fill Overlay 효과를 컬렉션의 끝에 추가합니다. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 새 Gray Scale 효과를 컬렉션의 끝에 추가합니다. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 새 Hue/Saturation/Luminance 효과를 컬렉션의 끝에 추가합니다. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 새 Luminance 효과를 컬렉션의 끝에 추가합니다. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 새 Tint 효과를 컬렉션의 끝에 추가합니다. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 새 BrightnessContrast 효과를 컬렉션의 끝에 추가합니다. |
| [size()](#size--) | 컬렉션에 포함된 이미지 효과 수를 반환합니다. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 가져옵니다. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | 새 이미지 효과를 컬렉션의 끝에 추가합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 이미지 효과를 제거합니다. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 지정된 Array 인덱스부터 Array에 복사합니다. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**Returns:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

[ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)를 컬렉션에서 인덱스로 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**Returns:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) 객체.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에서 컬렉션의 이미지 효과를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삭제할 이미지 효과의 인덱스. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

새 Alpha Bi-Level 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level 효과의 임계값. |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - 새 이미지 효과의 컬렉션 내 인덱스.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

새 Alpha Ceiling 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - 새 이미지 효과의 컬렉션 내 인덱스.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

새 Alpha Floor 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - 새 이미지 효과의 컬렉션 내 인덱스.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

새 Alpha Inverse 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - 새 이미지 효과의 컬렉션 내 인덱스.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

새 Alpha Modulate 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - 새 이미지 효과의 컬렉션 내 인덱스.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

새 Alpha Modulate Fixed 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| amount | float | 알파를 스케일링할 백분율 값. |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - 새 이미지 효과의 컬렉션 내 인덱스.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

새 Alpha Replace 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | float | 새 불투명도 값. |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - 새 이미지 효과의 컬렉션 내 인덱스.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

새 Bi-Level(흑백) 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threshold | float | Bi-Level 효과의 휘도 임계값. 임계값 이상은 흰색, 이하일 경우 검은색으로 설정됩니다. |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - 새 이미지 효과의 컬렉션 내 인덱스.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

새 Blur 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| radius | double | 블러 반경. |
| grow | boolean | 블러링 결과 객체 경계가 확장되는지 여부. true이면 경계가 확장되고, false이면 확장되지 않습니다. |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - 새 이미지 효과의 컬렉션 내 인덱스.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

새 Color Change 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - 새 이미지 효과의 컬렉션 내 인덱스.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

새 Color Replacement 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - 새 이미지 효과의 컬렉션 내 인덱스.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

새 Duotone 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - 새 이미지 효과의 컬렉션 내 인덱스.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

새 Fill Overlay 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - 새 이미지 효과의 컬렉션 내 인덱스.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

새 Gray Scale 효과를 컬렉션의 끝에 추가합니다.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - 새 이미지 효과의 컬렉션 내 인덱스.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

새 Hue/Saturation/Luminance 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hue | float | 색조를 조정하는 정도(도). |
| saturation | float | 채도를 조정하는 백분율. |
| luminance | float | 휘도를 조정하는 백분율. |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - 새 이미지 효과의 컬렉션 내 인덱스.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

새 Luminance 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brightness | float | 밝기를 변경할 백분율. |
| contrast | float | 대비를 변경할 백분율. |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - 새 이미지 효과의 컬렉션 내 인덱스.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

새 Tint 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hue | float | 색조를 지정합니다. |
| amount | float | 색상값이 이동하는 양을 지정합니다. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - 새 이미지 효과의 컬렉션 내 인덱스.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

새 BrightnessContrast 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| brightness | float | 밝기를 변경할 백분율. |
| contrast | float | 대비를 변경할 백분율. |

**Returns:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - 새 이미지 효과의 컬렉션 내 인덱스.

### size() {#size--}
```
public final int size()
```

컬렉션에 포함된 이미지 효과 수를 반환합니다. 읽기 전용 int .

**Returns:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용인지 여부를 가져옵니다. 읽기 전용 boolean.

**Returns:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)가 읽기 전용이면 true; 그렇지 않으면 false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

새 이미지 효과를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | 컬렉션의 끝에 추가할 이미지 효과. |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 객체. |

**Returns:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에 항목이 있으면 true; 없으면 false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)의 요소를 지정된 Array 인덱스부터 Array에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 복사된 요소를 저장할 일차원 Array. 0 기반 인덱싱이어야 합니다. |
| arrayIndex | int | 복사를 시작할 배열의 0 기반 인덱스. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 제거할 객체. |

**Returns:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 항목이 성공적으로 제거되면 true; 그렇지 않으면 false. 항목이 원본 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 없을 경우에도 false를 반환합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 컬렉션을 순회하는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - 전체 컬렉션에 대한 java.util.Iterator.