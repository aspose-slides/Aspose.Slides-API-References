---
title: FillOverlay
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Fill Overlay 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/filloverlay/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Fill Overlay 효과를 나타냅니다. Fill Overlay는 객체에 추가 채우기를 지정하고 두 채우기를 혼합하는 데 사용할 수 있습니다.
## Methods

| 메서드 | 설명 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Gets effective Fill Overlay effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [FillOverlay](../../com.aspose.slides/filloverlay) is equal to the current [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Fill format. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환값:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. 읽기/쓰기 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**반환값:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. 읽기/쓰기 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


상속이 적용된 효과적인 Fill Overlay 효과 데이터를 가져옵니다.

**반환값:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. 읽기 전용 long.

**반환값:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 [FillOverlay](../../com.aspose.slides/filloverlay)가 현재 [FillOverlay](../../com.aspose.slides/filloverlay)와 같은지 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [FillOverlay](../../com.aspose.slides/filloverlay). |

**반환값:**
boolean - 객체가 같으면 true, 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


특정 유형에 대한 해시 함수를 제공합니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.