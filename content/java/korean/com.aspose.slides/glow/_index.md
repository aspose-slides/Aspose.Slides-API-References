---
title: Glow
second_title: Aspose.Slides for Java API 참조
description: 객체의 가장자리 밖에 색상이 흐릿하게 흐려진 외곽선이 추가되는 Glow 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/glow/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Glow 효과를 나타내며, 객체의 가장자리 바깥에 색상이 흐릿하게 흐려진 외곽선이 추가됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRadius()](#getRadius--) | 반경. |
| [setRadius(double value)](#setRadius-double-) | 반경. |
| [getColor()](#getColor--) | 색상 형식. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Glow 효과 데이터를 가져옵니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [Glow](../../com.aspose.slides/glow)가 현재 [Glow](../../com.aspose.slides/glow)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


반경. 읽기/쓰기  double .

**반환:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


반경. 읽기/쓰기  double .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


색상 형식. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


상속이 적용된 효과적인 Glow 효과 데이터를 가져옵니다.

**반환:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
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


부모 IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 [Glow](../../com.aspose.slides/glow)가 현재 [Glow](../../com.aspose.slides/glow)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | [Glow](../../com.aspose.slides/glow)를 비교합니다. |

**반환:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


특정 유형에 대한 해시 함수를 제공합니다.

**반환:**
int - 현재 객체에 대한 해시 코드.