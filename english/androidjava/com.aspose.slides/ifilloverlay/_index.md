---
title: IFillOverlay
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a Fill Overlay effect.
type: docs
weight: 776
url: /androidjava/com.aspose.slides/ifilloverlay/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together.
## Methods

| Method | Description |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Read/write [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Returns:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Read/write [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill format. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
