---
title: Blur
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 채우기를 포함한 전체 도형에 적용되는 Blur 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/blur/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

전체 도형에 적용되는 Blur 효과를 나타냅니다. 채우기를 포함합니다. 알파를 포함한 모든 색상 채널이 영향을 받습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRadius()](#getRadius--) | blur 반경을 반환하거나 설정합니다. |
| [setRadius(double value)](#setRadius-double-) | blur 반경을 반환하거나 설정합니다. |
| [getGrow()](#getGrow--) | 블러링 결과 객체의 경계가 확대되어야 하는지 여부를 결정합니다. |
| [setGrow(boolean value)](#setGrow-boolean-) | 블러링 결과 객체의 경계가 확대되어야 하는지 여부를 결정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Blur 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [Blur](../../com.aspose.slides/blur)가 현재 [Blur](../../com.aspose.slides/blur)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 타입에 대한 해시 함수로 사용됩니다. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


blur 반경을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


blur 반경을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


블러링 결과 객체의 경계가 확대되어야 하는지 여부를 결정합니다. True는 경계가 확대됨을 나타내고 false는 그렇지 않음을 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


블러링 결과 객체의 경계가 확대되어야 하는지 여부를 결정합니다. True는 경계가 확대됨을 나타내고 false는 그렇지 않음을 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


상속이 적용된 효과적인 Blur 효과 데이터를 가져옵니다.

**반환:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 [Blur](../../com.aspose.slides/blur)가 현재 [Blur](../../com.aspose.slides/blur)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [Blur](../../com.aspose.slides/blur). |

**반환:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


특정 타입에 대한 해시 함수로 사용됩니다.

**반환:**
int - 현재 객체의 해시 코드.