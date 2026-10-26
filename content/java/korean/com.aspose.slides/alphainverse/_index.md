---
title: AlphaInverse
second_title: Aspose.Slides for Java API 레퍼런스
description: Alpha Inverse 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/alphainverse/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Alpha Inverse 효과를 나타냅니다. Alpha(불투명도) 값은 100%에서 빼서 반전됩니다.
## 메서드

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 Alpha Inverse 효과 데이터를 가져옵니다. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [AlphaInverse](../../com.aspose.slides/alphainverse) 가 현재 [AlphaInverse](../../com.aspose.slides/alphainverse) 와 동일한지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

상속이 적용된 Alpha Inverse 효과 데이터를 가져옵니다.

**반환값:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - 하나의 [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [AlphaInverse](../../com.aspose.slides/alphainverse) 가 현재 [AlphaInverse](../../com.aspose.slides/alphainverse) 와 같은지 여부를 판단합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [AlphaInverse](../../com.aspose.slides/alphainverse). |

**반환값:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공합니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.