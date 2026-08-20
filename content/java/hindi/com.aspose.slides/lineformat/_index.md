---
title: LineFormat
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक रेखा के फ़ॉर्मेट का प्रतिनिधित्व करता है।
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

एक रेखा के फ़ॉर्मेट का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Returns true if line format is not defined (as just created, default). |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns or sets the width of a line. |
| [setWidth(double value)](#setWidth-double-) | Returns or sets the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns or sets the line dash style. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Returns or sets the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns or sets the custom dash pattern. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Returns or sets the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns or sets the line cap style. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Returns or sets the line cap style. |
| [getStyle()](#getStyle--) | Returns or sets the line style. |
| [setStyle(byte value)](#setStyle-byte-) | Returns or sets the line style. |
| [getAlignment()](#getAlignment--) | Returns or sets the line alignment. |
| [setAlignment(byte value)](#setAlignment-byte-) | Returns or sets the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns or sets the lines join style. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Returns or sets the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns or sets the miter limit of a line. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Returns or sets the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns or sets the arrowhead style at the beginning of a line. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Returns or sets the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns or sets the arrowhead style at the end of a line. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Returns or sets the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns or sets the arrowhead width at the beginning of a line. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Returns or sets the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns or sets the arrowhead width at the end of a line. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Returns or sets the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns or sets the arrowhead length at the beginning of a line. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Returns or sets the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns or sets the arrowhead length at the end of a line. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Returns or sets the arrowhead length at the end of a line. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determines whether the two LineFormat instances are equal. |
| [getEffective()](#getEffective--) | Gets effective line formatting data with the inheritance applied. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**रिटर्न:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्दिष्ट वस्तु से तुलना करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**रिटर्न:**  
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

यदि रेखा फ़ॉर्मेट अपरिभाषित है (जैसे अभी बनाया गया, डिफ़ॉल्ट) तो true लौटाता है। केवल-पढ़ने योग्य boolean ।

**रिटर्न:**  
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

लाइन की भराव फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [ILineFillFormat](../../com.aspose.slides/ilinefillformat)।

**रिटर्न:**  
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

लाइन की स्केच फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [ILineFillFormat](../../com.aspose.slides/ilinefillformat)।

**रिटर्न:**  
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

रेखा की चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double।

**रिटर्न:**  
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

रेखा की चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

रेखा डैश शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle)।

**रिटर्न:**  
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

रेखा डैश शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineDashStyle](../../com.aspose.slides/linedashstyle)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

कस्टम डैश पैटर्न लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float[]।

**रिटर्न:**  
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

कस्टम डैश पैटर्न लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float[]।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

रेखा कैप शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle)।

**रिटर्न:**  
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

रेखा कैप शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineCapStyle](../../com.aspose.slides/linecapstyle)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

रेखा शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineStyle](../../com.aspose.slides/linestyle)।

**रिटर्न:**  
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

रेखा शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineStyle](../../com.aspose.slides/linestyle)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

रेखा अलाइनमेंट लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineAlignment](../../com.aspose.slides/linealignment)।

**रिटर्न:**  
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

रेखा अलाइनमेंट लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineAlignment](../../com.aspose.slides/linealignment)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

रेखा जॉइन शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle)।

**रिटर्न:**  
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

रेखा जॉइन शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineJoinStyle](../../com.aspose.slides/linejoinstyle)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

रेखा की मिटर सीमा लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**रिटर्न:**  
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

रेखा की मिटर सीमा लौटाता है या सेट करता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

रेखा की शुरुआत में एरोहेड शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**रिटर्न:**  
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

रेखा की शुरुआत में एरोहेड शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

रेखा के अंत में एरोहेड शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**रिटर्न:**  
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

रेखा के अंत में एरोहेड शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

रेखा की शुरुआत में एरोहेड चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**रिटर्न:**  
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

रेखा की शुरुआत में एरोहेड चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

रेखा के अंत में एरोहेड चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**रिटर्न:**  
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

रेखा के अंत में एरोहेड चौड़ाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

रेखा की शुरुआत में एरोहेड लंबाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**रिटर्न:**  
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

रेखा की शुरुआत में एरोहेड लंबाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

रेखा के अंत में एरोहेड लंबाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**रिटर्न:**  
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

रेखा के अंत में एरोहेड लंबाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

निर्धारित करता है कि दो LineFormat उदाहरण समान हैं या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | तुलना करने के लिये LineFormat। |

**रिटर्न:**  
boolean - **true** यदि निर्दिष्ट LineFormat वर्तमान LineFormat के समान है; अन्यथा **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

विरासत लागू होकर प्राप्त प्रभावी रेखा फ़ॉर्मेटिंग डेटा लौटाता है।

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
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - एक [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).