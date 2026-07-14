---
title: HSL
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 색조/채도/명도 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/hsl/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Hue/Saturation/Luminance 효과를 나타냅니다. 색조, 채도 및 명도는 각각 현재 값에 대해 조정될 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Hue/Saturation/Luminance 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [HSL](../../com.aspose.slides/hsl)가 현재 [HSL](../../com.aspose.slides/hsl)와 동일한지 확인합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수로 사용됩니다. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

상속이 적용된 효과적인 Hue/Saturation/Luminance 효과 데이터를 가져옵니다.

**반환값:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - 하나의 [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [HSL](../../com.aspose.slides/hsl)가 현재 [HSL](../../com.aspose.slides/hsl)와 동일한지 확인합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [HSL](../../com.aspose.slides/hsl). |

**반환값:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수로 사용됩니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.