---
title: IColorChange
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a Color Change effect.
type: docs
url: /com.aspose.slides/icolorchange/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor.
## Methods

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color which will be replaced. |
| [getToColor()](#getToColor--) | Color which will replace. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Color which will be replaced. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Color which will replace. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
