---
title: IPresetShadow
second_title: Aspose.Slides for Java API 레퍼런스
description: 프리셋 그림자 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ippresetshadow/
---
**모든 구현된 인터페이스:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

프리셋 그림자 효과를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 그림자의 방향. |
| [setDirection(float value)](#setDirection-float-) | 그림자의 방향. |
| [getDistance()](#getDistance--) | 그림자의 거리. |
| [setDistance(double value)](#setDistance-double-) | 그림자의 거리. |
| [getShadowColor()](#getShadowColor--) | 그림자의 색상. |
| [getPreset()](#getPreset--) | 프리셋. |
| [setPreset(int value)](#setPreset-int-) | 프리셋. |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

그림자의 방향. 읽기/쓰기 float.

**반환값:**  
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

그림자의 방향. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

그림자의 거리. 읽기/쓰기 double.

**반환값:**  
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

그림자의 거리. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

그림자의 색상. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

프리셋. 읽기/쓰기 [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**반환값:**  
int

### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

프리셋. 읽기/쓰기 [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |