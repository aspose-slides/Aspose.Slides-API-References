---
title: IColorChangeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which represents a Color Change effect.
type: docs
weight: 711
url: /com.aspose.slides/icolorchangeeffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Immutable object which represents a Color Change effect. Instances of FromColor are replaced with instances of ToColor.
## Methods

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color which will be replaced. |
| [getToColor()](#getToColor--) | Color which will replace. |
| [getUseAlpha()](#getUseAlpha--) | Returns a boolean value which determines if alpha component should be used. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Color which will be replaced. Read-only java.awt.Color.

**Returns:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Color which will replace. Read-only java.awt.Color.

**Returns:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Returns a boolean value which determines if alpha component should be used. Read-only boolean.

**Returns:**
boolean
