---
title: Tint
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Tint 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/tint/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.ITint](../../com.aspose.slides/itint), com.aspose.slides.IVisualEffect
```
public final class Tint extends ImageTransformOperation implements ITint, IVisualEffect
```

Tint 효과를 나타냅니다. 지정된 양만큼 색조를 향하거나 색조에서 멀어지도록 효과 색상 값을 이동시킵니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 유효한 Tint 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [Tint](../../com.aspose.slides/tint)가 현재 [Tint](../../com.aspose.slides/tint)와 동일한지 확인합니다. |
| [hashCode()](#hashCode--) | 특정 타입에 대한 해시 함수로 사용됩니다. |
### getEffective() {#getEffective--}
```
public final ITintEffectiveData getEffective()
```


상속이 적용된 유효한 Tint 효과 데이터를 가져옵니다.

**반환값:**
[ITintEffectiveData](../../com.aspose.slides/itinteffectivedata) - 하나의 [ITintEffectiveData](../../com.aspose.slides/itinteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 [Tint](../../com.aspose.slides/tint)가 현재 [Tint](../../com.aspose.slides/tint)와 동일한지 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [Tint](../../com.aspose.slides/tint). |

**반환값:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


특정 타입에 대한 해시 함수로 사용됩니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.