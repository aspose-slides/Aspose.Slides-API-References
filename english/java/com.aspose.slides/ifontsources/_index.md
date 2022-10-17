---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description:  Provides file and memory sources for external fonts.
type: docs
weight: 783
url: /java/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Provides file and memory sources for external fonts.
## Methods

| Method | Description |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Folders containing font files. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Folders containing font files. |
| [getMemoryFonts()](#getMemoryFonts--) | A collection of fonts represented as byte arrays. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | A collection of fonts represented as byte arrays. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Folders containing font files. All font files located in these folders are included in the collection. Folders that are recursively searched.

**Returns:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Folders containing font files. All font files located in these folders are included in the collection. Folders that are recursively searched.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


A collection of fonts represented as byte arrays.

**Returns:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


A collection of fonts represented as byte arrays.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |

