---
title: Duotone
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Duotone 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/duotone/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect  
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Duotone 효과를 나타냅니다. 각 픽셀에 대해 Color1과 Color2를 선형 보간을 통해 결합하여 해당 픽셀의 새로운 색상을 결정합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColor1()](#getColor1--) | 어두운 픽셀에 대한 대상 색상 형식을 반환합니다. |
| [getColor2()](#getColor2--) | 밝은 픽셀에 대한 대상 색상 형식을 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 Duotone 효과 데이터를 가져옵니다. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [Duotone](../../com.aspose.slides/duotone)가 현재 [Duotone](../../com.aspose.slides/duotone)와 같은지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 형식에 대한 해시 함수로 사용됩니다. |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

어두운 픽셀에 대한 대상 색상 형식을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

밝은 픽셀에 대한 대상 색상 형식을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

상속이 적용된 효과적인 Duotone 효과 데이터를 가져옵니다.

**반환:**  
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).

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

지정된 [Duotone](../../com.aspose.slides/duotone)가 현재 [Duotone](../../com.aspose.slides/duotone)와 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [Duotone](../../com.aspose.slides/duotone). |

**반환:**
boolean - 객체가 같으면 true; 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 형식에 대한 해시 함수로 사용됩니다.

**반환:**
int - 현재 객체에 대한 해시 코드입니다.