---
title: IColorChange
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 색상 변경 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icolorchange/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

색상 변경 효과를 나타냅니다. FromColor 인스턴스는 ToColor 인스턴스로 교체됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 교체될 색상. |
| [getToColor()](#getToColor--) | 대체할 색상. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


교체될 색상. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


대체할 색상. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)