---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: Stores theme-defined fonts.
type: docs
weight: 782
url: /androidjava/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Stores theme-defined fonts.
## Methods

| Method | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
| [setName(String value)](#setName-java.lang.String-) | Returns the font scheme name. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Returns the fonts collection for a "body" part of the slide. Read-only [IFonts](../../com.aspose.slides/ifonts).

**Returns:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Returns the fonts collection for a "heading" part of the slide. Read-only [IFonts](../../com.aspose.slides/ifonts).

**Returns:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Returns the font scheme name. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returns the font scheme name. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

