---
title: InnerShadow
second_title: Aspose.Slides for Java API 레퍼런스
description: 내부 그림자 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/innershadow/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

내부 그림자 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Blur radius. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Blur radius. |
| [getDirection()](#getDirection--) | Direction of shadow. |
| [setDirection(float value)](#setDirection-float-) | Direction of shadow. |
| [getDistance()](#getDistance--) | Distance of shadow. |
| [setDistance(double value)](#setDistance-double-) | Distance of shadow. |
| [getShadowColor()](#getShadowColor--) | Color of shadow. |
| [getEffective()](#getEffective--) | Gets effective Inner Shadow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [InnerShadow](../../com.aspose.slides/innershadow) is equal to the current [InnerShadow](../../com.aspose.slides/innershadow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

블러 반경. 읽기/쓰기 double.

**반환:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

블러 반경. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

그림자 방향. 읽기/쓰기 float.

**반환:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

그림자 방향. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

그림자 거리. 읽기/쓰기 double.

**반환:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

그림자 거리. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

그림자 색상. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

상속이 적용된 효과적인 내부 그림자 효과 데이터를 가져옵니다.

**반환:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - A [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 개체를 반환합니다. 읽기 전용 IDOMObject.

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

IPresentationComponent 부모를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [InnerShadow](../../com.aspose.slides/innershadow)가 현재 [InnerShadow](../../com.aspose.slides/innershadow)와 동일한지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [InnerShadow](../../com.aspose.slides/innershadow). |

**반환:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수 역할을 합니다.

**반환:**
int - 현재 객체에 대한 해시 코드.