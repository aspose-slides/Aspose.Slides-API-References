---
title: LineFormat
second_title: Aspose.Slides for Android के लिये Java API संदर्भ
description: लाइन के फ़ॉर्मेट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/lineformat/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

लाइन के फ़ॉर्मेट का प्रतिनिधित्व करता है।
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | यदि लाइन फ़ॉर्मेट निर्धारित नहीं है (जैसे अभी बना है, डिफ़ॉल्ट), तो true लौटाता है। |
| [getFillFormat()](#getFillFormat--) | लाइन के फ़िल फ़ॉर्मेट को लौटाता है। |
| [getSketchFormat()](#getSketchFormat--) | लाइन के स्केच फ़ॉर्मेट को लौटाता है। |
| [getWidth()](#getWidth--) | लाइन की चौड़ाई को लौटाता या सेट करता है। |
| [setWidth(double value)](#setWidth-double-) | लाइन की चौड़ाई को लौटाता या सेट करता है। |
| [getDashStyle()](#getDashStyle--) | लाइन का डैश शैली को लौटाता या सेट करता है। |
| [setDashStyle(byte value)](#setDashStyle-byte-) | लाइन का डैश शैली को लौटाता या सेट करता है। |
| [getCustomDashPattern()](#getCustomDashPattern--) | कस्टम डैश पैटर्न को लौटाता या सेट करता है। |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | कस्टम डैश पैटर्न को लौटाता या सेट करता है। |
| [getCapStyle()](#getCapStyle--) | लाइन के कैप शैली को लौटाता या सेट करता है। |
| [setCapStyle(byte value)](#setCapStyle-byte-) | लाइन के कैप शैली को लौटाता या सेट करता है। |
| [getStyle()](#getStyle--) | लाइन शैली को लौटाता या सेट करता है। |
| [setStyle(byte value)](#setStyle-byte-) | लाइन शैली को लौटाता या सेट करता है। |
| [getAlignment()](#getAlignment--) | लाइन संरेखण को लौटाता या सेट करता है। |
| [setAlignment(byte value)](#setAlignment-byte-) | लाइन संरेखण को लौटाता या सेट करता है। |
| [getJoinStyle()](#getJoinStyle--) | लाइन जॉइन शैली को लौटाता या सेट करता है। |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | लाइन जॉाइन शैली को लौटाता या सेट करता है। |
| [getMiterLimit()](#getMiterLimit--) | लाइन की मिटर सीमा को लौटाता या सेट करता है। |
| [setMiterLimit(float value)](#setMiterLimit-float-) | लाइन की मिटर सीमा को लौटाता या सेट करता है। |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | लाइन की शुरुआत में तीर के सिरे की शैली को लौटाता या सेट करता है। |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | लाइन की शुरुआत में तीर के सिरे की शैली को लौटाता या सेट करता है। |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | लाइन के अंत में तीर के सिरे की शैली को लौटाता या सेट करता है। |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | लाइन के अंत में तीर के सिरे की शैली को लौटाता या सेट करता है। |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | लाइन की शुरुआत में तीर के सिरे की चौड़ाई को लौटाता या सेट करता है। |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | लाइन की शुरुआत में तीर के सिरे की चौड़ाई को लौटाता या सेट करता है। |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | लाइन के अंत में तीर के सिरे की चौड़ाई को लौटाता या सेट करता है। |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | लाइन के अंत में तीर के सिरे की चौड़ाई को लौटाता या सेट करता है। |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | लाइन की शुरुआत में तीर के सिरे की लंबाई को लौटाता या सेट करता है। |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | लाइन की शुरुआत में तीर के सिरे की लंबाई को लौटाता या सेट करता है। |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | लाइन के अंत में तीर के सिरे की लंबाई को लौटाता या सेट करता है। |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | लाइन के अंत में तीर के सिरे की लंबाई को लौटाता या सेट करता है। |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | निर्धारित करता है कि दो LineFormat instances बराबर हैं या नहीं। |
| [getEffective()](#getEffective--) | विरासत लागू किए हुए प्रभावी लाइन फ़ॉर्मेट डेटा को प्राप्त करता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने-योग्य long।

**रिटर्न:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**रिटर्न:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

यदि लाइन फ़ॉर्मेट निर्धारित नहीं है (जैसे अभी बना है, डिफ़ॉल्ट), तो true लौटाता है। केवल-पढ़ने-योग्य boolean ।

**रिटर्न:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

लाइन के फ़िल फ़ॉर्मेट को लौटाता है। केवल-पढ़ने-योग्य [ILineFillFormat](../../com.aspose.slides/ilinefillformat)।

**रिटर्न:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

लाइन के स्केच फ़ॉर्मेट को लौटाता है। केवल-पढ़ने-योग्य [ILineFillFormat](../../com.aspose.slides/ilinefillformat)।

**रिटर्न:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```

लाइन की चौड़ाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य double ।

**रिटर्न:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

लाइन की चौड़ाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य double ।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

लाइन का डैश शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle)।

**रिटर्न:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

लाइन का डैश शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

कस्टम डैश पैटर्न को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य float[] ।

**रिटर्न:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

कस्टम डैश पैटर्न को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य float[] ।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

लाइन के कैप शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle)।

**रिटर्न:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

लाइन के कैप शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```

लाइन शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineStyle](../../com.aspose.slides/linestyle)।

**रिटर्न:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

लाइन शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineStyle](../../com.aspose.slides/linestyle)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

लाइन संरेखण को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineAlignment](../../com.aspose.slides/linealignment)।

**रिटर्न:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

लाइन संरेखण को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineAlignment](../../com.aspose.slides/linealignment)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

लाइन जॉइन शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle)।

**रिटर्न:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

लाइन जॉइन शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

लाइन की मिटर सीमा को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य float ।

**रिटर्न:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

लाइन की मिटर सीमा को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य float ।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

लाइन की शुरुआत में तीर के सिरे की शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**रिटर्न:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

लाइन की शुरुआत में तीर के सिरे की शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

लाइन के अंत में तीर के सिरे की शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**रिटर्न:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

लाइन के अंत में तीर के सिरे की शैली को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

लाइन की शुरुआत में तीर के सिरे की चौड़ाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**रिटर्न:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

लाइन की शुरुआत में तीर के सिरे की चौड़ाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

लाइन के अंत में तीर के सिरे की चौड़ाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**रिटर्न:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

लाइन के अंत में तीर के सिरे की चौड़ाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

लाइन की शुरुआत में तीर के सिरे की लंबाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**रिटर्न:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

लाइन की शुरुआत में तीर के सिरे की लंबाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

लाइन के अंत में तीर के सिरे की लंबाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**रिटर्न:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

लाइन के अंत में तीर के सिरे की लंबाई को लौटाता या सेट करता है। पढ़ने/लिखने-योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

निर्धारित करता है कि दो LineFormat instances बराबर हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | वर्तमान LineFormat के साथ तुलना करने के लिए LineFormat। |

**रिटर्न:**
boolean - **true** यदि निर्दिष्ट LineFormat वर्तमान LineFormat के बराबर है; अन्यथा, **false**।
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

विरासत लागू किए हुए प्रभावी लाइन फ़ॉर्मेट डेटा को प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).