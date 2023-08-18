---
title: MasterTheme
second_title: Aspose.Slides for Java API Reference
description: Represents a master theme.
type: docs
weight: 304
url: /com.aspose.slides/mastertheme/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public class MasterTheme extends Theme implements IMasterTheme
```

Represents a master theme.
## Methods

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Returns the collection of additional color schemes. |
| [getName()](#getName--) | Returns the name of a theme. |
| [setName(String value)](#setName-java.lang.String-) | Returns the name of a theme. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


Returns the color scheme. Read-only [IColorScheme](../../com.aspose.slides/icolorscheme).

**Returns:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


Returns the font scheme. Read-only [IFontScheme](../../com.aspose.slides/ifontscheme).

**Returns:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


Returns the shape format scheme. Read-only [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Returns:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


Returns the collection of additional color schemes. These schemes don't affect presentation's look, they can be selected as main color scheme for a slide. Read-only [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Returns:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


Returns the name of a theme. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Returns the name of a theme. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
