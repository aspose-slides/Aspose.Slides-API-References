---
title: ILineFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक रेखा का फ़ॉर्मेट दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ilineformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

लाइन के फ़ॉर्मेट को दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | यदि लाइन फ़ॉर्मेट परिभाषित नहीं है (जैसे अभी बनाया गया, डिफ़ॉल्ट) तो true लौटाता है। |
| [getFillFormat()](#getFillFormat--) | लाइन का भराव फ़ॉर्मेट लौटाता है। |
| [getSketchFormat()](#getSketchFormat--) | लाइन का स्केच फ़ॉर्मेट लौटाता है। |
| [getWidth()](#getWidth--) | लाइन की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setWidth(double value)](#setWidth-double-) | लाइन की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [getDashStyle()](#getDashStyle--) | लाइन डैश शैली को प्राप्त करता है या सेट करता है। |
| [setDashStyle(byte value)](#setDashStyle-byte-) | लाइन डैश शैली को प्राप्त करता है या सेट करता है। |
| [getCustomDashPattern()](#getCustomDashPattern--) | कस्टम डैश पैटर्न को प्राप्त करता है या सेट करता है। |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | कस्टम डैश पैटर्न को प्राप्त करता है या सेट करता है। |
| [getCapStyle()](#getCapStyle--) | लाइन कैप शैली को प्राप्त करता है या सेट करता है। |
| [setCapStyle(byte value)](#setCapStyle-byte-) | लाइन कैप शैली को प्राप्त करता है या सेट करता है। |
| [getStyle()](#getStyle--) | लाइन शैली को प्राप्त करता है या सेट करता है। |
| [setStyle(byte value)](#setStyle-byte-) | लाइन शैली को प्राप्त करता है या सेट करता है। |
| [getAlignment()](#getAlignment--) | लाइन संरेखण को प्राप्त करता है या सेट करता है। |
| [setAlignment(byte value)](#setAlignment-byte-) | लाइन संरेखण को प्राप्त करता है या सेट करता है। |
| [getJoinStyle()](#getJoinStyle--) | लाइन जॉइन शैली को प्राप्त करता है या सेट करता है। |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | लाइन जॉइन शैली को प्राप्त करता है या सेट करता है। |
| [getMiterLimit()](#getMiterLimit--) | लाइन की मिटर सीमा को प्राप्त करता है या सेट करता है। |
| [setMiterLimit(float value)](#setMiterLimit-float-) | लाइन की मिटर सीमा को प्राप्त करता है या सेट करता है। |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | लाइन की शुरुआत में एरोहेड शैली को प्राप्त करता है या सेट करता है। |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | लाइन की शुरुआत में एरोहेड शैली को प्राप्त करता है या सेट करता है। |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | लाइन के अंत में एरोहेड शैली को प्राप्त करता है या सेट करता है। |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | लाइन के अंत में एरोहेड शैली को प्राप्त करता है या सेट करता है। |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | लाइन की शुरुआत में एरोहेड चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | लाइन की शुरुआत में एरोहेड चौड़ाई को प्राप्त करता है या सेट करता है। |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | लाइन के अंत में एरोहेड चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | लाइन के अंत में एरोहेड चौड़ाई को प्राप्त करता है या सेट करता है। |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | लाइन की शुरुआत में एरोहेड लंबाई को प्राप्त करता है या सेट करता है। |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | लाइन की शुरुआत में एरोहेड लंबाई को प्राप्त करता है या सेट करता है। |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | लाइन के अंत में एरोहेड लंबाई को प्राप्त करता है या सेट करता है। |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | लाइन के अंत में एरोहेड लंबाई को प्राप्त करता है या सेट करता है। |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | निर्धारित करता है कि दो LineFormat इंस्टेंस समान हैं या नहीं। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी लाइन फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

यदि लाइन फ़ॉर्मेट परिभाषित नहीं है (जैसे अभी बनाया गया, डिफ़ॉल्ट) तो true लौटाता है। केवल पढ़ने योग्य boolean।

**परिणाम:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

लाइन का भराव फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [ILineFillFormat](../../com.aspose.slides/ilinefillformat)।

**परिणाम:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

लाइन का स्केच फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [ISketchFormat](../../com.aspose.slides/isketchformat)।

**परिणाम:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

लाइन की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य double।

**परिणाम:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

लाइन की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

लाइन डैश शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle)।

**परिणाम:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

लाइन डैश शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

कस्टम डैश पैटर्न को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य float[]।

**परिणाम:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

कस्टम डैश पैटर्न को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य float[]।

**परामीटर:**
| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

लाइन कैप शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle)।

**परिणाम:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

लाइन कैप शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

लाइन शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineStyle](../../com.aspose.slides/linestyle)।

**परिणाम:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

लाइन शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineStyle](../../com.aspose.slides/linestyle)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

लाइन संरेखण को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineAlignment](../../com.aspose.slides/linealignment)।

**परिणाम:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

लाइन संरेखण को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineAlignment](../../com.aspose.slides/linealignment)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

लाइन जॉइन शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle)।

**परिणाम:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

लाइन जॉइन शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

लाइन की मिटर सीमा को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य float।

**परिणाम:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

लाइन की मिटर सीमा को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य float।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

लाइन की शुरुआत में एरोहेड शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**परिणाम:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

लाइन की शुरुआत में एरोहेड शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

लाइन के अंत में एरोहेड शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**परिणाम:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

लाइन के अंत में एरोहेड शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

लाइन की शुरुआत में एरोहेड चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**परिणाम:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

लाइन की शुरुआत में एरोहेड चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

लाइन के अंत में एरोहेड चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**परिणाम:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

लाइन के अंत में एरोहेड चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

लाइन की शुरुआत में एरोहेड लंबाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**परिणाम:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

लाइन की शुरुआत में एरोहेड लंबाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

लाइन के अंत में एरोहेड लंबाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**परिणाम:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

लाइन के अंत में एरोहेड लंबाई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

निर्धारित करता है कि दो LineFormat इंस्टेंस समान हैं या नहीं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | वर्तमान LineFormat के साथ तुलना करने वाला LineFormat। |

**परिणाम:**
boolean - **true** यदि निर्दिष्ट LineFormat वर्तमान LineFormat के बराबर है; अन्यथा, **false**।

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

विरासत लागू करके प्रभावी लाइन फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**परिणाम:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - एक [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).