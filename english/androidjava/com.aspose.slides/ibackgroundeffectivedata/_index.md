---
title: IBackgroundEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective background properties.
type: docs
weight: 654
url: /androidjava/com.aspose.slides/ibackgroundeffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

Immutable object which contains effective background properties.

--------------------

This interface is used together with the [IBackground](../../com.aspose.slides/ibackground) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns effective fill format. |
| [getEffectFormat()](#getEffectFormat--) | Returns effective effect format. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Returns effective fill format. Read-only [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Returns effective effect format. Read-only [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Returns:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
