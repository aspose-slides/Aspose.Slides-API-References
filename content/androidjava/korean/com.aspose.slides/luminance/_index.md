---
title: Luminance
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Luminance 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/luminance/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Luminance 효과를 나타냅니다. 밝기는 모든 색상을 흰색 또는 검은색에 더 가깝게 선형으로 이동시킵니다. 대비는 모든 색상이 더 가깝게 또는 더 멀리 떨어지도록 스케일링합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 유효 Luminance 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [Luminance](../../com.aspose.slides/luminance)가 현재 [Luminance](../../com.aspose.slides/luminance)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |
### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```

상속이 적용된 유효 Luminance 효과 데이터를 가져옵니다.

**반환:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - 하나의 [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [Luminance](../../com.aspose.slides/luminance)가 현재 [Luminance](../../com.aspose.slides/luminance)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [Luminance](../../com.aspose.slides/luminance). |

**반환:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공합니다.

**반환:**
int - 현재 객체의 해시 코드.