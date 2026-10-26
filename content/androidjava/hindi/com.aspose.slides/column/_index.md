---
title: Column
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक तालिका में कॉलम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/column/
---
**विरासत:** java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)  
```
public final class Column extends CellCollection implements IColumn
```

एक टेबल में कॉलम का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | कॉलम की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setWidth(double value)](#setWidth-double-) | कॉलम की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | सभी कॉलम सेल्स के portion फ़ॉर्मेट गुण सेट करता है। |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | सभी कॉलम सेल्स के paragraph फ़ॉर्मेट गुण सेट करता है। |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | सभी कॉलम सेल्स के text frame फ़ॉर्मेट गुण सेट करता है। |
| [getColumnFormat()](#getColumnFormat--) | एक ColumnFormat ऑब्जेक्ट लौटाता है जिसमें इस कॉलम के लिए फ़ॉर्मेटिंग गुण होते हैं। |

### getWidth() {#getWidth--}
```
public final double getWidth()
```

कॉलम की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें double.

**रिटर्न:**  
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

कॉलम की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

सभी कॉलम सेल्स के portion फ़ॉर्मेट गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat ऑब्जेक्ट जिसमें आवश्यक गुण सेट किए गए हैं। |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

सभी कॉलम सेल्स के paragraph फ़ॉर्मेट गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat ऑब्जेक्ट जिसमें आवश्यक गुण सेट किए गए हैं। |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

सभी कॉलम सेल्स के text frame फ़ॉर्मेट गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat ऑब्जेक्ट जिसमें आवश्यक गुण सेट किए गए हैं। |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

एक ColumnFormat ऑब्जेक्ट लौटाता है जिसमें इस कॉलम के लिए फ़ॉर्मेटिंग गुण होते हैं। केवल-पढ़ने योग्य [IColumnFormat](../../com.aspose.slides/icolumnformat)।

**रिटर्न:**  
[IColumnFormat](../../com.aspose.slides/icolumnformat)