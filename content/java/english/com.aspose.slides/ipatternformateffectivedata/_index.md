---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /com.aspose.slides/ipatternformateffectivedata/
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
| [getTileImage(Color background, Color foreground)](#getTileImage-java.awt.Color-java.awt.Color-) | Creates a tile image for the pattern fill with a specified colors. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Returns the pattern style. Read-only [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Returns the foreground pattern color. Read-only java.awt.Color.

**Returns:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Returns the background pattern color. Read-only java.awt.Color.

**Returns:**
java.awt.Color
### getTileImage(Color background, Color foreground) {#getTileImage-java.awt.Color-java.awt.Color-}
```
public abstract BufferedImage getTileImage(Color background, Color foreground)
```


Creates a tile image for the pattern fill with a specified colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | The background java.awt.Color for the pattern. |
| foreground | java.awt.Color | The foreground java.awt.Color for the pattern. |

**Returns:**
java.awt.image.BufferedImage - Tile java.awt.image.BufferedImage.
