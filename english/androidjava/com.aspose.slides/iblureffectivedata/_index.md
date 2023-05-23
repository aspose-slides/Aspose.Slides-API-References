---
title: IBlurEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which represents a Blur effect that is applied to the entire shape including its fill.
type: docs
weight: 673
url: /androidjava/com.aspose.slides/iblureffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Immutable object which represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected.
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Returns or sets blur radius. |
| [getGrow()](#getGrow--) | Determines whether the bounds of the object should be grown as a result of the blurring. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Returns or sets blur radius. Read-only double.

**Returns:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Determines whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. Read-only boolean.

**Returns:**
boolean
