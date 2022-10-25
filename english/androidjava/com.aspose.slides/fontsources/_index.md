---
title: FontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
weight: 206
url: /androidjava/com.aspose.slides/fontsources/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

Provides file and memory sources for external fonts.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontSources()](#FontSources--) | Creates new default font options. |
## Methods

| Method | Description |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Folders containing font files. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Folders containing font files. |
| [getMemoryFonts()](#getMemoryFonts--) | A collection of fonts represented as byte arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | A collection of fonts represented as byte arrays. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Creates new default font options.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Folders containing font files. All font files located in these folders are included in the collection. Folders that are recursively searched.

**Returns:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Folders containing font files. All font files located in these folders are included in the collection. Folders that are recursively searched.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


A collection of fonts represented as byte arrays.

**Returns:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


A collection of fonts represented as byte arrays.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |

