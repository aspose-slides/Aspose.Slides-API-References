---
title: Column
second_title: जावा के लिए Aspose.Slides API संदर्भ
description: एक तालिका में कॉलम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/column/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

तालिका में एक कॉलम का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | कॉलम की चौड़ाई को लौटाता या सेट करता है। |
| [setWidth(double value)](#setWidth-double-) | कॉलम की चौड़ाई को लौटाता या सेट करता है। |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | सभी कॉलम कोशिकाओं के भागों पर परिभाषित भाग फ़ॉर्मेट गुण सेट करता है। |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | सभी कॉलम कोशिकाओं के पैराग्राफों पर परिभाषित पैराग्राफ फ़ॉर्मेट गुण सेट करता है। |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | सभी कॉलम कोशिकाओं के टेक्स्ट फ्रेम पर परिभाषित टेक्स्ट फ्रेम फ़ॉर्मेट गुण सेट करता है। |
| [getColumnFormat()](#getColumnFormat--) | इस कॉलम के लिए फॉर्मेटिंग गुणों को रखने वाले ColumnFormat ऑब्जेक्ट को लौटाता है। |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

कॉलम की चौड़ाई को लौटाता या सेट करता है। पढ़ें/लिखें double.

**वापसी:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

कॉलम की चौड़ाई को लौटाता या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

सभी कॉलम कोशिकाओं के भागों पर परिभाषित भाग फ़ॉर्मेट गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | आवश्यक गुण सेट किए हुए IPortionFormat ऑब्जेक्ट। |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

सभी कॉलम कोशिकाओं के पैराग्राफों पर परिभाषित पैराग्राफ फ़ॉर्मेट गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | आवश्यक गुण सेट किए हुए IParagraphFormat ऑब्जेक्ट। |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

सभी कॉलम कोशिकाओं के टेक्स्ट फ्रेम पर परिभाषित टेक्स्ट फ्रेम फ़ॉर्मेट गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | आवश्यक गुण सेट किए हुए ITextFrameFormat ऑब्जेक्ट। |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

इस कॉलम के लिए फॉर्मेटिंग गुणों को रखने वाले ColumnFormat ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IColumnFormat](../../com.aspose.slides/icolumnformat)।

**वापसी:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)