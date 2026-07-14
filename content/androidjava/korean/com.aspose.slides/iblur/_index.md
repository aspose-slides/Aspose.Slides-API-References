---
title: IBlur
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 전체 도형 및 채우기에 적용되는 블러 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iblur/
---
**구현된 모든 인터페이스:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

전체 도형 및 채우기를 포함하여 적용되는 블러 효과를 나타냅니다. 알파를 포함한 모든 색상 채널이 영향을 받습니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRadius()](#getRadius--) | Blur 반경을 반환하거나 설정합니다. |
| [setRadius(double value)](#setRadius-double-) | Blur 반경을 반환하거나 설정합니다. |
| [getGrow()](#getGrow--) | 블러링 결과 객체의 경계가 확대되어야 하는지 여부를 결정합니다. |
| [setGrow(boolean value)](#setGrow-boolean-) | 블러링 결과 객체의 경계가 확대되어야 하는지 여부를 결정합니다. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Blur 반경을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환값:**  
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Blur 반경을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

블러링 결과 객체의 경계가 확대되어야 하는지 여부를 결정합니다. True는 경계가 확대됨을 의미하고 false는 그렇지 않음을 의미합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

블러링 결과 객체의 경계가 확대되어야 하는지 여부를 결정합니다. True는 경계가 확대됨을 의미하고 false는 그렇지 않음을 의미합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |