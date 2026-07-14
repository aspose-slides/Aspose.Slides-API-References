---
title: IFillOverlay
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Fill Overlay 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ifilloverlay/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Fill Overlay 효과를 나타냅니다. Fill Overlay는 객체에 추가 채우기를 지정하고 두 채우기를 혼합하는 데 사용할 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. 읽기/쓰기 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**반환:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. 읽기/쓰기 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)