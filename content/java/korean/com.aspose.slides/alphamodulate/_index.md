---
title: AlphaModulate
second_title: Aspose.Slides for Java API 레퍼런스
description: Alpha Modulate 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/alphamodulate/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

Alpha Modulate 효과를 나타냅니다. 효과 알파(불투명도) 값은 고정 비율로 곱해집니다. 효과 컨테이너는 알파 값을 변조하는 효과를 지정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Modulate effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaModulate](../../com.aspose.slides/alphamodulate) is equal to the current [AlphaModulate](../../com.aspose.slides/alphamodulate). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```


Gets effective Alpha Modulate effect data with the inheritance applied.

**반환값:**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 [AlphaModulate](../../com.aspose.slides/alphamodulate)가 현재 [AlphaModulate](../../com.aspose.slides/alphamodulate)와 같은지 여부를 판단합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [AlphaModulate](../../com.aspose.slides/alphamodulate). |

**반환값:**
boolean - 객체가 같으면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


특정 유형에 대한 해시 함수를 제공합니다.

**반환값:**
int - 현재 객체의 해시 코드.