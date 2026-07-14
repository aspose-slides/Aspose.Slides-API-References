---
title: AlphaModulateFixed
second_title: Aspose.Slides for Android Java API 참조
description: Alpha Modulate Fixed 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/alphamodulatefixed/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

Alpha Modulate Fixed 효과를 나타냅니다. 효과 알파 (opacity) 값은 고정된 비율로 곱해집니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAmount()](#getAmount--) | 효과 양을 퍼센트 단위로 반환합니다. |
| [setAmount(float value)](#setAmount-float-) | 효과 양을 퍼센트 단위로 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 유효한 Alpha Modulate Fixed 효과 데이터를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)가 현재 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)와 동일한지 판단합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |
### getAmount() {#getAmount--}
```
public final float getAmount()
```

효과 양을 퍼센트 단위로 반환합니다. 읽기/쓰기 float.

**반환값:**
float
### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```

효과 양을 퍼센트 단위로 반환합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```

상속이 적용된 유효한 Alpha Modulate Fixed 효과 데이터를 가져옵니다.

**반환값:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)가 현재 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)와 동일한지 판단합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed). |

**반환값:**
boolean - 객체가 동일하면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수로 사용됩니다.

**반환값:**
int - 현재 객체에 대한 해시 코드.