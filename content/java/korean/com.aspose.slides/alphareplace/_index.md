---
title: AlphaReplace
second_title: Aspose.Slides Java API 참조
description: Alpha Replace 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/alphareplace/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAlphaReplace](../../com.aspose.slides/ialphareplace), com.aspose.slides.IVisualEffect  
```
public final class AlphaReplace extends ImageTransformOperation implements IAlphaReplace, IVisualEffect
```

Alpha Replace 효과를 나타냅니다. 효과 알파(불투명도) 값이 고정 알파로 교체됩니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Alpha Replace 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [AlphaReplace](../../com.aspose.slides/alphareplace)가 현재 [AlphaReplace](../../com.aspose.slides/alphareplace)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 형식에 대한 해시 함수 역할을 합니다. |

### getEffective() {#getEffective--}
```
public final IAlphaReplaceEffectiveData getEffective()
```

상속이 적용된 효과적인 Alpha Replace 효과 데이터를 가져옵니다.

**반환:**  
[IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata) - A [IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [AlphaReplace](../../com.aspose.slides/alphareplace)가 현재 [AlphaReplace](../../com.aspose.slides/alphareplace)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [AlphaReplace](../../com.aspose.slides/alphareplace). |

**반환:**  
boolean - 객체가 같으면 true; 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 형식에 대한 해시 함수 역할을 합니다.

**반환:**  
int - 현재 객체에 대한 해시 코드.