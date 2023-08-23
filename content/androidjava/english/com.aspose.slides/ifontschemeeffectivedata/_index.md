---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective font scheme properties.
type: docs
url: /com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Immutable object which contains effective font scheme properties.

--------------------

This interface is used as a part of [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Returns the fonts collection for a "body" part of the slide. Read-only [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Returns:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Returns the fonts collection for a "heading" part of the slide. Read-only [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Returns:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Returns the font scheme name. Read-only String.

**Returns:**
java.lang.String
