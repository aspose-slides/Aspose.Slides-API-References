---
title: ColorReplace
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 색상 교체 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/colorreplace/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable  
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

색상 교체 효과를 나타냅니다. 모든 효과 색상이 고정 색상으로 변경됩니다. 알파 값은 영향을 받지 않습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColor()](#getColor--) | 각 픽셀의 색상을 교체할 색상 포맷을 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 유효한 색상 교체 효과 데이터를 가져옵니다. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [ColorReplace](../../com.aspose.slides/colorreplace)가 현재 [ColorReplace](../../com.aspose.slides/colorreplace)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

각 픽셀의 색상을 교체할 색상 포맷을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

상속이 적용된 유효한 색상 교체 효과 데이터를 가져옵니다.

**반환:**  
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - 하나의 [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 [ColorReplace](../../com.aspose.slides/colorreplace)가 현재 [ColorReplace](../../com.aspose.slides/colorreplace)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [ColorReplace](../../com.aspose.slides/colorreplace). |

**반환:**  
boolean - 객체가 같으면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공합니다.

**반환:**  
int - 현재 객체의 해시 코드.