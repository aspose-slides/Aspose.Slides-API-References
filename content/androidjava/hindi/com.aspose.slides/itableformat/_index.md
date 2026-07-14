---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: एक तालिका के प्रारूप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

एक तालिका के प्रारूप का प्रतिनिधित्व करता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a table fill properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Returns a table fill properties object. केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Gets or sets the transparency of the fill color. पढ़ें/लिखें  float .

**रिटर्न:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Gets or sets the transparency of the fill color. पढ़ें/लिखें  float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

Gets effective table formatting properties with inheritance and table styles applied.

**रिटर्न:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - एक [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).