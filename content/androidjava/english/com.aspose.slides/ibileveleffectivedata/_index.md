---
title: IBiLevelEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which represents a Bi-Level black/white effect.
type: docs
weight: 669
url: /com.aspose.slides/ibileveleffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Immutable object which represents a Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect.
## Methods

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returns the threshold value. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Returns the threshold value. Read-only float.

**Returns:**
float
