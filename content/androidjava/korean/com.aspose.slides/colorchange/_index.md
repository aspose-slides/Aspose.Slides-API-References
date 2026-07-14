---
title: ColorChange
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 색상 변경 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/colorchange/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**구현된 모든 인터페이스:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

색상 변경 효과를 나타냅니다. FromColor 인스턴스는 ToColor 인스턴스로 교체됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 교체될 색상. |
| [getToColor()](#getToColor--) | 교체할 색상. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 색상 변경 데이터를 가져옵니다. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 [ColorChange](../../com.aspose.slides/colorchange)가 현재 [ColorChange](../../com.aspose.slides/colorchange)와 같은지 여부를 확인합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공합니다. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

교체될 색상. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

교체할 색상. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

상속이 적용된 효과적인 색상 변경 데이터를 가져옵니다.

**반환값:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - 하나의 [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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

지정된 [ColorChange](../../com.aspose.slides/colorchange)가 현재 [ColorChange](../../com.aspose.slides/colorchange)와 같은지 여부를 확인합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 [ColorChange](../../com.aspose.slides/colorchange). |

**반환값:**
boolean - 객체가 같은 경우 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공합니다.

**반환값:**
int - 현재 객체의 해시 코드.