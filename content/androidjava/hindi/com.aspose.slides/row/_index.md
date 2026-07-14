---
title: Row
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
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
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeight()](#getHeight--) | पंक्ति की ऊँचाई लौटाता है। |
| [getMinimalHeight()](#getMinimalHeight--) | पंक्ति की न्यूनतम संभावित ऊँचाई लौटाता है या सेट करता है। |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | पंक्ति की न्यूनतम संभावित ऊँचाई लौटाता है या सेट करता है। |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | सभी पंक्ति कोशिकाओं के भागों पर परिभाषित portion format गुण सेट करता है। |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | सभी पंक्ति कोशिकाओं के अनुच्छेदों पर परिभाषित paragraph format गुण सेट करता है। |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | सभी पंक्ति कोशिकाओं के टेक्स्ट फ़्रेम्स पर परिभाषित text frame format गुण सेट करता है। |
| [getRowFormat()](#getRowFormat--) | पंक्ति के लिए फ़ॉर्मेटिंग गुणों को शामिल करने वाले RowFormat वस्तु को लौटाता है। |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


पंक्ति की ऊँचाई लौटाता है। केवल-पढ़ने योग्य double।

**वापसी:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


पंक्ति की न्यूनतम संभावित ऊँचाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double।

**वापसी:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


पंक्ति की न्यूनतम संभावित ऊँचाई लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


सभी पंक्ति कोशिकाओं के भागों पर परिभाषित portion format गुण सेट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | आवश्यक गुणों के साथ IPortionFormat वस्तु। |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


सभी पंक्ति कोशिकाओं के अनुच्छेदों पर परिभाषित paragraph format गुण सेट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | आवश्यक गुणों के साथ IParagraphFormat वस्तु। |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


सभी पंक्ति कोशिकाओं के टेक्स्ट फ़्रेम्स पर परिभाषित text frame format गुण सेट करता है।

**परामी터:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | आवश्यक गुणों के साथ ITextFrameFormat वस्तु। |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


पंक्ति के लिए फ़ॉर्मेटिंग गुणों को शामिल करने वाले RowFormat वस्तु को लौटाता है। केवल-पढ़ने योग्य [IRowFormat](../../com.aspose.slides/irowformat)।

**वापसी:**
[IRowFormat](../../com.aspose.slides/irowformat)