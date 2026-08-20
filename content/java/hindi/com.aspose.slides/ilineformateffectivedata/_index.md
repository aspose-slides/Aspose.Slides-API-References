---
title: ILineFormatEffectiveData
second_title: Aspose.Slides for Java API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो प्रभावी रेखा फ़ॉर्मेटिंग गुणों को सम्मिलित करती है।
type: docs
url: /hi/com.aspose.slides/ilineformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

एक अपरिवर्तनीय वस्तु जो प्रभावी रेखा फ़ॉर्मेटिंग गुणों को सम्मिलित करती है।

--------------------

यह इंटरफ़ेस [ILineFormat](../../com.aspose.slides/ilineformat) इंटरफ़ेस के साथ मिलकर उपयोग किया जाता है ताकि विरासत लागू किए हुए प्रभावी फ़ॉर्मेटिंग मान लौटाए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns the line cap style. |
| [getStyle()](#getStyle--) | Returns the line style. |
| [getAlignment()](#getAlignment--) | Returns the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns the arrowhead length at the end of a line. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Determines whether the two ILineFormatEffectiveData instances are equal. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


एक रेखा का fill format लौटाता है। केवल-पढ़ने के लिए [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**वापसी:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


एक रेखा का sketch format लौटाता है। केवल-पढ़ने के लिए [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**वापसी:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


एक रेखा की चौड़ाई लौटाता है। केवल-पढ़ने के लिए double.

**वापसी:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


रेखा का dash style लौटाता है। केवल-पढ़ने के लिए [LineDashStyle](../../com.aspose.slides/linedashstyle).

**वापसी:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


कस्टम dash pattern लौटाता है। केवल-पढ़ने के लिए float[].

**वापसी:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


रेखा का cap style लौटाता है। केवल-पढ़ने के लिए [LineCapStyle](../../com.aspose.slides/linecapstyle).

**वापसी:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


रेखा का style लौटाता है। केवल-पढ़ने के लिए [LineStyle](../../com.aspose.slides/linestyle).

**वापसी:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


रेखा का alignment लौटाता है। केवल-पढ़ने के लिए [LineAlignment](../../com.aspose.slides/linealignment).

**वापसी:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


रेखा के join style को लौटाता है। केवल-पढ़ने के लिए [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**वापसी:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


रेखा का miter limit लौटाता है। केवल-पढ़ने के लिए float.

**वापसी:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


रेखा की शुरुआत में arrowhead style लौटाता है। केवल-पढ़ने के लिए [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**वापसी:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


रेखा के अंत में arrowhead style लौटाता है। केवल-पढ़ने के लिए [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**वापसी:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


रेखा की शुरुआत में arrowhead width लौटाता है। केवल-पढ़ने के लिए [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**वापसी:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


रेखा के अंत में arrowhead width लौटाता है। केवल-पढ़ने के लिए [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**वापसी:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


रेखा की शुरुआत में arrowhead length लौटाता है। केवल-पढ़ने के लिए [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**वापसी:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


रेखा के अंत में arrowhead length लौटाता है। केवल-पढ़ने के लिए [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**वापसी:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


निर्धारित करता है कि दो ILineFormatEffectiveData इंस्टेंस बराबर हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | वर्तमान ILineFormatEffectiveData के साथ तुलना करने के लिए ILineFormatEffectiveData। |

**वापसी:**
boolean - **true** यदि निर्दिष्ट ILineFormatEffectiveData वर्तमान ILineFormatEffectiveData के बराबर है; अन्यथा, **false**.