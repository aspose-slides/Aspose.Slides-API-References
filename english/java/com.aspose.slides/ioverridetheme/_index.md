---
title: IOverrideTheme
second_title: Aspose.Slides for Java API Reference
description: Represents a overriding theme.
type: docs
weight: 951
url: /java/com.aspose.slides/ioverridetheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Represents a overriding theme.
## Methods

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | True value means that ColorScheme, FontScheme, FormatScheme is null and any overriding with this theme object are disabled. |
| [initColorScheme()](#initColorScheme--) | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [clear()](#clear--) | Set ColorScheme, FontScheme, FormatScheme to null to disable any overriding with this theme object. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```


True value means that ColorScheme, FontScheme, FormatScheme is null and any overriding with this theme object are disabled. Read-only boolean.

**Returns:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```


Init ColorScheme with new object for overriding ColorScheme of InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```


Init ColorScheme with new object for overriding ColorScheme of InheritedTheme.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Data to initialize from. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```


Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. And initialize data of this new object with data of the ColorScheme of InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```


Init FontScheme with new object for overriding FontScheme of InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```


Init FontScheme with new object for overriding FontScheme of InheritedTheme.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Data to initialize from. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```


Init FontScheme with new object for overriding FontScheme of InheritedTheme. And initialize data of this new object with data of the FontScheme of InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```


Init FormatScheme with new object for overriding FormatScheme of InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```


Init FormatScheme with new object for overriding FormatScheme of InheritedTheme.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Data to initialize from. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```


Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. And initialize data of this new object with data of the FormatScheme of InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```


Set ColorScheme, FontScheme, FormatScheme to null to disable any overriding with this theme object.

