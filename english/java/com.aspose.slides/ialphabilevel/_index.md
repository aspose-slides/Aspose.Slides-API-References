---
title: IAlphaBiLevel
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an Alpha Bi-Level effect.
type: docs
weight: 624
url: /java/com.aspose.slides/ialphabilevel/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque).

--------------------

Use ImageTransformOperationFactory to create instaces in COM.
## Methods

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returns effect threshold. |
| [setThreshold(float value)](#setThreshold-float-) | Returns effect threshold. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Returns effect threshold. Read/write float.

**Returns:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Returns effect threshold. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

