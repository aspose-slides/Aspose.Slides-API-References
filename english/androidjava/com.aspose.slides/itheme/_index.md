---
title: ITheme
second_title: Aspose.Slides for Java API Reference
description: Represents a theme.
type: docs
weight: 1072
url: /java/com.aspose.slides/itheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Represents a theme.
## Methods

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
| [getEffective()](#getEffective--) | Gets effective theme data with the inheritance applied. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


Returns the color scheme. Read-only [IColorScheme](../../com.aspose.slides/icolorscheme).

**Returns:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


Returns the font scheme. Read-only [IFontScheme](../../com.aspose.slides/ifontscheme).

**Returns:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


Returns the shape format scheme. Read-only [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Returns:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


Gets effective theme data with the inheritance applied.

**Returns:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
