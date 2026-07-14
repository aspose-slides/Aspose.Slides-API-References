---
title: IDuotone
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: Duotone 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iduotone/
---
**구현된 모든 인터페이스:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IDuotone extends IImageTransformOperation, IAccessiblePVIObject<IDuotoneEffectiveData>
```

Duotone 효과를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColor1()](#getColor1--) | 어두운 픽셀에 대한 대상 색상 형식을 반환합니다. |
| [getColor2()](#getColor2--) | 밝은 픽셀에 대한 대상 색상 형식을 반환합니다. |
### getColor1() {#getColor1--}
```
public abstract IColorFormat getColor1()
```

어두운 픽셀에 대한 대상 색상 형식을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public abstract IColorFormat getColor2()
```

밝은 픽셀에 대한 대상 색상 형식을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**  
[IColorFormat](../../com.aspose.slides/icolorformat)