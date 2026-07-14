---
title: PresetShadow
second_title: Aspose.Slides for Android Java API 참조
description: 프리셋 섀도우 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/presetshadow/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

프리셋 섀도우 효과를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 그림자 방향. |
| [setDirection(float value)](#setDirection-float-) | 그림자 방향. |
| [getDistance()](#getDistance--) | 그림자 거리. |
| [setDistance(double value)](#setDistance-double-) | 그림자 거리. |
| [getShadowColor()](#getShadowColor--) | 그림자 색상. |
| [getPreset()](#getPreset--) | 프리셋. |
| [setPreset(int value)](#setPreset-int-) | 프리셋. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 프리셋 섀도우 효과 데이터를 얻습니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [PresetShadow](../../com.aspose.slides/presetshadow)이 현재 [PresetShadow](../../com.aspose.slides/presetshadow)와 동일한지 확인합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

그림자 방향. 읽기/쓰기  float .

**반환:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

그림자 방향. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

그림자 거리. 읽기/쓰기  double .

**반환:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

그림자 거리. 읽기/쓰기  double .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

그림자 색상. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public final int getPreset()
```

프리셋. 읽기/쓰기 [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**반환:**
int

### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

프리셋. 읽기/쓰기 [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

상속이 적용된 효과적인 프리셋 섀도우 효과 데이터를 얻습니다.

**반환:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

버전. 읽기 전용 long.

**반환:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [PresetShadow](../../com.aspose.slides/presetshadow)이 현재 [PresetShadow](../../com.aspose.slides/presetshadow)와 동일한지 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [PresetShadow](../../com.aspose.slides/presetshadow). |

**반환:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공합니다.

**반환:**
int - 현재 객체의 해시 코드.