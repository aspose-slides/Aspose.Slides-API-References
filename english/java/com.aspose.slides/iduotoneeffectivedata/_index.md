---
title: IDuotoneEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which represents a Duotone effect.
type: docs
weight: 755
url: /java/com.aspose.slides/iduotoneeffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Immutable object which represents a Duotone effect. For each pixel, combines clr1 and clr2 through a linear interpolation to determine the new color for that pixel.
## Methods

| Method | Description |
| --- | --- |
| [getColor1()](#getColor1--) | Returns target color format for dark pixels. |
| [getColor2()](#getColor2--) | Returns target color format for light pixels. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Returns target color format for dark pixels. Read-only java.awt.Color.

**Returns:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Returns target color format for light pixels. Read-only java.awt.Color.

**Returns:**
java.awt.Color
