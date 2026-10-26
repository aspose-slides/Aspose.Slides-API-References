---
title: SoftEdge
second_title: Aspose.Slides for Android용 Java API 참조
description: 소프트 엣지 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/softedge/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

소프트 엣지 효과를 나타냅니다. 모양의 가장자리는 흐려지지만 채우기는 영향을 받지 않습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRadius()](#getRadius--) | 가장자리에 적용할 흐림 반경을 지정합니다. |
| [setRadius(double value)](#setRadius-double-) | 가장자리에 적용할 흐림 반경을 지정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 유효한 Soft Edge 효과 데이터를 가져옵니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [SoftEdge](../../com.aspose.slides/softedge)가 현재 [SoftEdge](../../com.aspose.slides/softedge)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수 역할을 합니다. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


가장자리에 적용할 흐림 반경을 지정합니다. 읽기/쓰기 double.

**반환값:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


가장자리에 적용할 흐림 반경을 지정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


상속이 적용된 유효한 Soft Edge 효과 데이터를 가져옵니다.

**반환값:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - 하나의 [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


버전. 읽기 전용 long.

**반환값:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


부모 IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환값:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 [SoftEdge](../../com.aspose.slides/softedge)가 현재 [SoftEdge](../../com.aspose.slides/softedge)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [SoftEdge](../../com.aspose.slides/softedge). |

**반환값:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


특정 유형에 대한 해시 함수 역할을 합니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.