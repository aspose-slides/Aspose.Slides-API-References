---
title: ILineFormat
second_title: Android के लिए Aspose.Slides Java API संदर्भ
description: एक लाइन का फ़ॉर्मेट दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ilineformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

एक लाइन का फ़ॉर्मेट दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | यदि लाइन फ़ॉर्मेट निर्धारित नहीं किया गया है (जैसे अभी बनाया गया, डिफ़ॉल्ट) तो true लौटाता है। |
| [getFillFormat()](#getFillFormat--) | लाइन के fill फ़ॉर्मेट को लौटाता है। |
| [getSketchFormat()](#getSketchFormat--) | लाइन के sketch फ़ॉर्मेट को लौटाता है। |
| [getWidth()](#getWidth--) | लाइन की चौड़ाई को लौटाता है या सेट करता है। |
| [setWidth(double value)](#setWidth-double-) | लाइन की चौड़ाई को लौटाता है या सेट करता है। |
| [getDashStyle()](#getDashStyle--) | लाइन dash शैली को लौटाता है या सेट करता है। |
| [setDashStyle(byte value)](#setDashStyle-byte-) | लाइन dash शैली को लौटाता है या सेट करता है। |
| [getCustomDashPattern()](#getCustomDashPattern--) | कस्टम dash पैटर्न को लौटाता है या सेट करता है। |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | कस्टम dash पैटर्न को लौटाता है या सेट करता है। |
| [getCapStyle()](#getCapStyle--) | लाइन cap शैली को लौटाता है या सेट करता है। |
| [setCapStyle(byte value)](#setCapStyle-byte-) | लाइन cap शैली को लौटाता है या सेट करता है। |
| [getStyle()](#getStyle--) | लाइन शैली को लौटाता है या सेट करता है। |
| [setStyle(byte value)](#setStyle-byte-) | लाइन शैली को लौटाता है या सेट करता है। |
| [getAlignment()](#getAlignment--) | लाइन संरेखण को लौटाता है या सेट करता है। |
| [setAlignment(byte value)](#setAlignment-byte-) | लाइन संरेखण को लौटाता है या सेट करता है। |
| [getJoinStyle()](#getJoinStyle--) | लाइन जॉइन शैली को लौटाता है या सेट करता है। |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | लाइन जॉइन शैली को लौटाता है या सेट करता है। |
| [getMiterLimit()](#getMiterLimit--) | लाइन की miter सीमा को लौटाता है या सेट करता है। |
| [setMiterLimit(float value)](#setMiterLimit-float-) | लाइन की miter सीमा को लौटाता है या सेट करता है। |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | लाइन की शुरुआत में arrowhead शैली को लौटाता है या सेट करता है। |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | लाइन की शुरुआत में arrowhead शैली को लौटाता है या सेट करता है। |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | लाइन के अंत में arrowhead शैली को लौटाता है या सेट करता है। |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | लाइन के अंत में arrowhead शैली को लौटाता है या सेट करता है। |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | लाइन की शुरुआत में arrowhead चौड़ाई को लौटाता है या सेट करता है। |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | लाइन की शुरुआत में arrowhead चौड़ाई को लौटाता है या सेट करता है। |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | लाइन के अंत में arrowhead चौड़ाई को लौटाता है या सेट करता है। |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | लाइन के अंत में arrowhead चौड़ाई को लौटाता है या सेट करता है। |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | लाइन की शुरुआत में arrowhead लंबाई को लौटाता है या सेट करता है। |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | लाइन की शुरुआत में arrowhead लंबाई को लौटाता है या सेट करता है। |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | लाइन के अंत में arrowhead लंबाई को लौटाता है या सेट करता है। |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | लाइन के अंत में arrowhead लंबाई को लौटाता है या सेट करता है। |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | निर्धारित करता है कि दो LineFormat इंस्टेंसेज़ समान हैं या नहीं। |
| [getEffective()](#getEffective--) | इनहेरिटेंस लागू करके प्रभावी लाइन फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

यदि लाइन फ़ॉर्मेट निर्धारित नहीं किया गया है (जैसे अभी बनाया गया, डिफ़ॉल्ट) तो true लौटाता है। केवल पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

लाइन के fill फ़ॉर्मेट को लौटाता है। केवल पढ़ने योग्य [ILineFillFormat](../../com.aspose.slides/ilinefillformat)।

**रिटर्न:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

लाइन के sketch फ़ॉर्मेट को लौटाता है। केवल पढ़ने योग्य [ISketchFormat](../../com.aspose.slides/isketchformat)।

**रिटर्न:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

लाइन की चौड़ाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double।

**रिटर्न:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

लाइन की चौड़ाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

लाइन dash शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle)।

**रिटर्न:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

लाइन dash शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

कस्टम dash पैटर्न को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float[]।

**रिटर्न:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

कस्टम dash पैटर्न को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float[]।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

लाइन cap शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle)।

**रिटर्न:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

लाइन cap शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

लाइन शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineStyle](../../com.aspose.slides/linestyle)।

**रिटर्न:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

लाइन शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineStyle](../../com.aspose.slides/linestyle)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

लाइन संरेखण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineAlignment](../../com.aspose.slides/linealignment)।

**रिटर्न:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

लाइन संरेखण को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineAlignment](../../com.aspose.slides/linealignment)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

लाइन जॉइन शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle)।

**रिटर्न:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

लाइन जॉइन शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

लाइन की miter सीमा को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

लाइन की miter सीमा को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

लाइन की शुरुआत में arrowhead शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**रिटर्न:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

लाइन की शुरुआत में arrowhead शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

लाइन के अंत में arrowhead शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**रिटर्न:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

लाइन के अंत में arrowhead शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

लाइन की शुरुआत में arrowhead चौड़ाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**रिटर्न:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

लाइन की शुरुआत में arrowhead चौड़ाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

लाइन के अंत में arrowhead चौड़ाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**रिटर्न:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

लाइन के अंत में arrowhead चौड़ाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

लाइन की शुरुआत में arrowhead लंबाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**रिटर्न:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

लाइन की शुरुआत में arrowhead लंबाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

लाइन के अंत में arrowhead लंबाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**रिटर्न:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

लाइन के अंत में arrowhead लंबाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

निर्धारित करता है कि दो LineFormat इंस्टेंसेज़ समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | वर्तमान LineFormat के साथ तुलना करने हेतु LineFormat। |

**रिटर्न:**
boolean - **true** यदि निर्दिष्ट LineFormat वर्तमान LineFormat के बराबर है; अन्यथा **false**।
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

इनहेरिटेंस लागू करके प्रभावी लाइन फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**रिटर्न:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - एक [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)।