---
title: OverrideTheme
second_title: Aspose.Slides for Java API Reference
description: Represents a overriding theme.
type: docs
weight: 396
url: /java/com.aspose.slides/overridetheme/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**All Implemented Interfaces:**
[com.aspose.slides.IOverrideTheme](../../com.aspose.slides/ioverridetheme)
```
public class OverrideTheme extends Theme implements IOverrideTheme
```

Represents a overriding theme.
## Methods

| Method | Description |
| --- | --- |
| [initColorScheme()](#initColorScheme--) | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [getColorScheme()](#getColorScheme--) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
| [isEmpty()](#isEmpty--) | True value means that ColorScheme, FontScheme, FormatScheme is null and any overriding with this theme object are disabled. |
| [clear()](#clear--) | Set ColorScheme, FontScheme, FormatScheme to null to disable any overriding with this theme object. |
| [getVersion()](#getVersion--) |  |
### initColorScheme() {#initColorScheme--}
```
public final void initColorScheme()
```


Init ColorScheme with new object for overriding ColorScheme of InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public final void initColorSchemeFrom(IColorScheme colorScheme)
```


Init ColorScheme with new object for overriding ColorScheme of InheritedTheme.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Data to initialize from. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public final void initColorSchemeFromInherited()
```


Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. And initialize data of this new object with data of the ColorScheme of InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public final void initFontScheme()
```


Init FontScheme with new object for overriding FontScheme of InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public final void initFontSchemeFrom(IFontScheme fontScheme)
```


Init FontScheme with new object for overriding FontScheme of InheritedTheme.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Data to initialize from. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public final void initFontSchemeFromInherited()
```


Init FontScheme with new object for overriding FontScheme of InheritedTheme. And initialize data of this new object with data of the FontScheme of InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public final void initFormatScheme()
```


Init FormatScheme with new object for overriding FormatScheme of InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public final void initFormatSchemeFrom(IFormatScheme formatScheme)
```


Init FormatScheme with new object for overriding FormatScheme of InheritedTheme.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Data to initialize from. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public final void initFormatSchemeFromInherited()
```


Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. And initialize data of this new object with data of the FormatScheme of InheritedTheme.

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
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


True value means that ColorScheme, FontScheme, FormatScheme is null and any overriding with this theme object are disabled. Read-only boolean.

**Returns:**
boolean
### clear() {#clear--}
```
public final void clear()
```


Set ColorScheme, FontScheme, FormatScheme to null to disable any overriding with this theme object.

### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
