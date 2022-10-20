---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
weight: 958
url: /androidjava/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Immutable object which contains effective pattern filling properties.

--------------------

This interface is used as a part of [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) and [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTileImage(Integer background, Integer foreground)](#getTileImage-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Returns the pattern style. Read-only [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Returns the foreground pattern color. Read-only java.lang.Integer.

**Returns:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Returns the background pattern color. Read-only java.lang.Integer.

**Returns:**
java.lang.Integer
### getTileImage(Integer background, Integer foreground) {#getTileImage-java.lang.Integer-java.lang.Integer-}
```
public abstract Bitmap getTileImage(Integer background, Integer foreground)
```


Creates a tile image for the pattern fill with a specified colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | The background java.lang.Integer for the pattern. |
| foreground | java.lang.Integer | The foreground java.lang.Integer for the pattern. |

**Returns:**
android.graphics.Bitmap - Tile android.graphics.Bitmap.
