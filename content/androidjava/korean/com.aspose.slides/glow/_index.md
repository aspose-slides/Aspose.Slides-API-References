---
title: Glow
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 오브젝트 가장자리 바깥에 색상이 흐려진 윤곽선을 추가하는 Glow 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/glow/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

오브젝트 가장자리 바깥에 색상이 흐려진 윤곽선을 추가하는 Glow 효과를 나타냅니다.
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | 반경. |
| [setRadius(double value)](#setRadius-double-) | 반경. |
| [getColor()](#getColor--) | 색상 형식. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Glow 효과 데이터를 가져옵니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [Glow](../../com.aspose.slides/glow)가 현재 [Glow](../../com.aspose.slides/glow)와 같은지 확인합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

반경. 읽기/쓰기 double .

**Returns:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

반경. 읽기/쓰기 double .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

색상 형식. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

상속이 적용된 효과적인 Glow 효과 데이터를 가져옵니다.

**Returns:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

버전. 읽기 전용 long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

부모 IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [Glow](../../com.aspose.slides/glow)가 현재 [Glow](../../com.aspose.slides/glow)와 같은지 확인합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [Glow](../../com.aspose.slides/glow). |

**Returns:**
boolean - 객체가 같은 경우 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공합니다.

**Returns:**
int - 현재 객체의 해시 코드.