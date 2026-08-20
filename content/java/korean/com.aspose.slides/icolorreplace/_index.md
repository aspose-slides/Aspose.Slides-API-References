---
title: IColorReplace
second_title: Aspose.Slides Java API 참조
description: 색상 교체 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icolorreplace/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorReplace extends IImageTransformOperation, IAccessiblePVIObject<IColorReplaceEffectiveData>
```

Color Replacement 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColor()](#getColor--) | 각 픽셀의 색상을 교체할 색상 형식을 반환합니다. |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


각 픽셀의 색상을 교체할 색상 형식을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**
[IColorFormat](../../com.aspose.slides/icolorformat)