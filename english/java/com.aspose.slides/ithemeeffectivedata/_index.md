---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description:  Immutable object which contains effective theme properties.
type: docs
weight: 1072
url: /java/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Immutable object which contains effective theme properties.

--------------------

This interface is used together with the [ITheme](../../com.aspose.slides/itheme) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Returns the color scheme.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Returns:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Color scheme [IColorSchemeEffectiveData](../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Returns the font scheme. Read-only [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Returns:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Returns the shape format scheme. Read-only [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Returns:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)
