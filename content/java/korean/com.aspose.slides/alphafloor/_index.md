---
title: AlphaFloor
second_title: Aspose.Slides for Java API 레퍼런스
description: Alpha Floor 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/alphafloor/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Alpha Floor 효과를 나타냅니다. Alpha(불투명도) 값이 100% 미만인 경우 0으로 변경됩니다. 즉, 부분적으로 투명한 모든 것이 완전히 투명해집니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 유효 Alpha Floor 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [AlphaFloor](../../com.aspose.slides/alphafloor)가 현재 [AlphaFloor](../../com.aspose.slides/alphafloor)와 같은지 판단합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


상속이 적용된 유효 Alpha Floor 효과 데이터를 가져옵니다.

**반환값:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 [AlphaFloor](../../com.aspose.slides/alphafloor)가 현재 [AlphaFloor](../../com.aspose.slides/alphafloor)와 같은지 판단합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [AlphaFloor](../../com.aspose.slides/alphafloor). |

**반환값:**
boolean - 객체가 같으면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


특정 유형에 대한 해시 함수를 제공합니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.