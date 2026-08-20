---
title: Row
second_title: Aspose.Slides for Java API संदर्भ
description: एक तालिका में पंक्ति का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/row/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IRow](../../com.aspose.slides/irow)  
```
public final class Row extends CellCollection implements IRow
```

एक तालिका में पंक्ति का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getHeight()](#getHeight--) | पंक्ति की ऊँचाई लौटाता है। |
| [getMinimalHeight()](#getMinimalHeight--) | पंक्ति की न्यूनतम संभव ऊँचाई को लौटाता या सेट करता है। |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | पंक्ति की न्यूनतम संभव ऊँचाई को लौटाता या सेट करता है। |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | सभी पंक्ति सेल के भागों पर परिभाषित भाग फॉर्मेट गुण सेट करता है। |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | सभी पंक्ति सेल के अनुच्छेदों पर परिभाषित पैराग्राफ फॉर्मेट गुण सेट करता है। |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | सभी पंक्ति सेल के टेक्स्ट फ्रेम पर परिभाषित टेक्स्ट फ्रेम फॉर्मेट गुण सेट करता है। |
| [getRowFormat()](#getRowFormat--) | वह RowFormat ऑब्जेक्ट लौटाता है जो इस पंक्ति के फ़ॉर्मेटिंग गुणों को समाहित करता है। |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

पंक्ति की ऊँचाई लौटाता है। केवल पढ़ने योग्य double.

**रिटर्न:**  
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

पंक्ति की न्यूनतम संभव ऊँचाई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**  
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

पंक्ति की न्यूनतम संभव ऊँचाई को लौटाता या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

सभी पंक्ति सेल के भागों पर परिभाषित भाग फॉर्मेट गुण सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | आवश्यक गुणों के साथ सेट किया गया IPortionFormat ऑब्जेक्ट। |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

सभी पंक्ति सेल के अनुच्छेदों पर परिभाषित पैराग्राफ फॉर्मेट गुण सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | आवश्यक गुणों के साथ सेट किया गया IParagraphFormat ऑब्जेक्ट। |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

सभी पंक्ति सेल के टेक्स्ट फ्रेम पर परिभाषित टेक्स्ट फ्रेम फॉर्मेट गुण सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | आवश्यक गुणों के साथ सेट किया गया ITextFrameFormat ऑब्जेक्ट। |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

इस पंक्ति के फ़ॉर्मेटिंग गुणों को समाहित करने वाला RowFormat ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IRowFormat](../../com.aspose.slides/irowformat)।

**रिटर्न:**  
[IRowFormat](../../com.aspose.slides/irowformat)