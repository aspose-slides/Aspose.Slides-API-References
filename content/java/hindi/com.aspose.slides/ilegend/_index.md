---
title: ILegend
second_title: Aspose.Slides for Java API संदर्भ
description: चार्ट की लेजेंड गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ilegend/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

चार्ट की लेजेंड गुणों का प्रतिनिधित्व करता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap legend. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap legend. |
| [getPosition()](#getPosition--) | Specifies the position of the legend on a chart. |
| [setPosition(int value)](#setPosition-int-) | Specifies the position of the legend on a chart. |
| [getFormat()](#getFormat--) | Returns the format of a legend. |
| [getEntries()](#getEntries--) | Gets legend entries. |

### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Determines whether other chart elements shall be allowed to overlap legend. Read/write boolean.

**रिटर्न्स:**
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Determines whether other chart elements shall be allowed to overlap legend. Read/write boolean.

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Heigt properties override effect of this property. Read/write [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**रिटर्न्स:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Heigt properties override effect of this property. Read/write [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Returns the format of a legend. Read-only [IFormat](../../com.aspose.slides/iformat).

**रिटर्न्स:**
[IFormat](../../com.aspose.slides/iformat)

### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Gets legend entries. Read-only [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**रिटर्न्स:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)