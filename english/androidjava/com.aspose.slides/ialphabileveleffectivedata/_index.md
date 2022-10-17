---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description:  Immutable object which represents an Alpha Bi-Level effect.
type: docs
weight: 625
url: /androidjava/com.aspose.slides/ialphabileveleffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Immutable object which represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque).
## Methods

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returns effect threshold. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Returns effect threshold. Read-only float.

**Returns:**
float
