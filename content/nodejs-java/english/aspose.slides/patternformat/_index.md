---
title: PatternFormat
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/patternformat/
---

## PatternFormat class

 Represents a pattern to fill a shape.
 
### getBackColor {#getBackColor}

| Name | Description |
| --- | --- |
| getBackColor () | Returns the background pattern color. Read-only IColorFormat. |

 **Result:**
[ColorFormat](../colorformat)


---


### getForeColor {#getForeColor}

| Name | Description |
| --- | --- |
| getForeColor () | Returns the foreground pattern color. Read-only IColorFormat. |

 **Result:**
[ColorFormat](../colorformat)


---


### getPatternStyle {#getPatternStyle}

| Name | Description |
| --- | --- |
| getPatternStyle () | Returns or sets the pattern style. Read/write PatternStyle. |

 **Result:**
byte


---


### getTileImage {#getTileImage}

| Name | Description |
| --- | --- |
| getTileImage (Color, Color) | Creates a tile image for the pattern fill with a specified colors. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| background | Color | The background java.awt.Color for the pattern. |
| foreground | Color | The foreground java.awt.Color for the pattern. |

 **Result:**
BufferedImage


---


### getTileImage {#getTileImage}

| Name | Description |
| --- | --- |
| getTileImage (Color) | Creates a tile image for the pattern fill. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| styleColor | Color | The default java.awt.Color, defined in ShapeEx's StyleEx object. Fill's colors can depend on this. |

 **Result:**
BufferedImage


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Result:**
long


---


### setPatternStyle {#setPatternStyle}

| Name | Description |
| --- | --- |
| setPatternStyle (byte) | Returns or sets the pattern style. Read/write PatternStyle. |


---


