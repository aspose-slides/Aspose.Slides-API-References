---
title: GrayScale
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 그레이 스케일 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/grayscale/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Gray Scale 효과를 나타냅니다. 모든 효과 색상 값을 그 밝기에 해당하는 회색 음영으로 변환합니다. 효과 알파(불투명도) 값은 영향을 받지 않습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Gray Scale 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [GrayScale](../../com.aspose.slides/grayscale)가 현재 [GrayScale](../../com.aspose.slides/grayscale)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수 역할을 합니다. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

상속이 적용된 효과적인 Gray Scale 효과 데이터를 가져옵니다.

**반환:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [GrayScale](../../com.aspose.slides/grayscale)가 현재 [GrayScale](../../com.aspose.slides/grayscale)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [GrayScale](../../com.aspose.slides/grayscale). |

**반환:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수 역할을 합니다.

**반환:**
int - 현재 객체에 대한 해시 코드.