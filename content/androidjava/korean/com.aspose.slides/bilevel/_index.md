---
title: BiLevel
second_title: Aspose.Slides for Android용 Java API 참조
description: Bi-Level 흑백 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/bilevel/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Bi-Level(흑백) 효과를 나타냅니다. 지정된 임계값보다 낮은 휘도 값을 가진 입력 색상은 검은색으로 변경됩니다. 지정된 값보다 크거나 같거나 같은 휘도 값을 가진 입력 색상은 흰색으로 설정됩니다. 알파 효과 값은 이 효과에 영향을 받지 않습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Bi-Level 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [BiLevel](../../com.aspose.slides/bilevel)가 현재 [BiLevel](../../com.aspose.slides/bilevel)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수로 사용됩니다. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

상속이 적용된 효과적인 Bi-Level 효과 데이터를 가져옵니다.

**반환값:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [BiLevel](../../com.aspose.slides/bilevel)가 현재 [BiLevel](../../com.aspose.slides/bilevel)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [BiLevel](../../com.aspose.slides/bilevel). |

**반환값:**
boolean - 객체가 같으면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수로 사용됩니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.