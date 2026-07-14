---
title: AlphaCeiling
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: Alpha Ceiling 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/alphaceiling/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect  
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Alpha Ceiling 효과를 나타냅니다. Alpha (opacity) 값이 0보다 큰 경우 100%로 변경됩니다. 다시 말해, 부분적으로 불투명한 모든 것이 완전히 불투명해집니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Alpha Ceiling 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [AlphaCeiling](../../com.aspose.slides/alphaceiling)가 현재 [AlphaCeiling](../../com.aspose.slides/alphaceiling)와 동일한지 확인합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |

### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

상속이 적용된 효과적인 Alpha Ceiling 효과 데이터를 가져옵니다.

**반환값:**  
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - A [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [AlphaCeiling](../../com.aspose.slides/alphaceiling)가 현재 [AlphaCeiling](../../com.aspose.slides/alphaceiling)와 동일한지 확인합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [AlphaCeiling](../../com.aspose.slides/alphaceiling). |

**반환값:**  
boolean - 객체가 동일하면 true; 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공합니다.

**반환값:**  
int - 현재 객체에 대한 해시 코드.