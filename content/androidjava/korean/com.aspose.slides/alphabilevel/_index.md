---
title: AlphaBiLevel
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Alpha Bi-Level 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/alphabilevel/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect  
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Alpha Bi-Level 효과를 나타냅니다. 임계값보다 작은 Alpha(Opacity) 값은 0(완전 투명)으로 변경되고, 임계값보다 크거나 같은 alpha 값은 100%(완전 불투명)으로 변경됩니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 효과 임계값을 반환합니다. |
| [setThreshold(float value)](#setThreshold-float-) | 효과 임계값을 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Alpha Bi-Level 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)가 현재 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)와 같은지 확인합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수로 사용됩니다. |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

효과 임계값을 반환합니다. 읽기/쓰기 float.

**반환값:**  
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

효과 임계값을 반환합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

상속이 적용된 효과적인 Alpha Bi-Level 효과 데이터를 가져옵니다.

**반환값:**  
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)가 현재 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)와 같은지 확인합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel)를 비교할 대상. |

**반환값:**
boolean - 객체가 동일하면 true, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수로 사용됩니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.