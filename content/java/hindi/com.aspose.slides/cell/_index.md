---
title: Cell
second_title: Aspose.Slides for Java API संदर्भ
description: एक टेबल की एक सेल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/cell/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

एक टेबल की एक सेल का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | टेबल की बाएँ पक्ष से सेल के बाएँ पक्ष तक की दूरी लौटाता है। |
| [getOffsetY()](#getOffsetY--) | टेबल की शीर्ष पक्ष से सेल के शीर्ष पक्ष तक की दूरी लौटाता है। |
| [getFirstRowIndex()](#getFirstRowIndex--) | सेल द्वारा कवर की गई पहली पंक्ति का अनुक्रमांक लौटाता है। |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | सेल द्वारा कवर किए गए पहले कॉलम का अनुक्रमांक लौटाता है। |
| [getWidth()](#getWidth--) | सेल की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | सेल की ऊँचाई लौटाता है। |
| [getMinimalHeight()](#getMinimalHeight--) | सेल की न्यूनतम ऊँचाई लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | टेक्स्टफ़्रेम में बाएँ मार्जिन लौटाता या सेट करता है। |
| [setMarginLeft(double value)](#setMarginLeft-double-) | टेक्स्टफ़्रेम में बाएँ मार्जिन लौटाता या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | टेक्स्टफ़्रेम में दाएँ मार्जिन लौटाता या सेट करता है। |
| [setMarginRight(double value)](#setMarginRight-double-) | टेक्स्टफ़्रेम में दाएँ मार्जिन लौटाता या सेट करता है। |
| [getMarginTop()](#getMarginTop--) | टेक्स्टफ़्रेम में शीर्ष मार्जिन लौटाता या सेट करता है। |
| [setMarginTop(double value)](#setMarginTop-double-) | टेक्स्टफ़्रेम में शीर्ष मार्जिन लौटाता या सेट करता है। |
| [getMarginBottom()](#getMarginBottom--) | टेक्स्टफ़्रेम में नीचे मार्जिन लौटाता या सेट करता है। |
| [setMarginBottom(double value)](#setMarginBottom-double-) | टेक्स्टफ़्रेम में नीचे मार्जिन लौटाता या सेट करता है। |
| [getTextVerticalType()](#getTextVerticalType--) | वर्टिकल टेक्स्ट का प्रकार लौटाता या सेट करता है। |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | वर्टिकल टेक्स्ट का प्रकार लौटाता या सेट करता है। |
| [getTextAnchorType()](#getTextAnchorType--) | टेक्स्ट एंकर प्रकार लौटाता या सेट करता है। |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | टेक्स्ट एंकर प्रकार लौटाता या सेट करता है। |
| [getAnchorCenter()](#getAnchorCenter--) | निर्धारित करता है कि क्या टेक्स्ट बॉक्स सेल के अंदर केंद्रित है। |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | निर्धारित करता है कि क्या टेक्स्ट बॉक्स सेल के अंदर केंद्रित है। |
| [getFirstRow()](#getFirstRow--) | सेल की पहली पंक्ति प्राप्त करता है। |
| [getFirstColumn()](#getFirstColumn--) | सेल का पहला कॉलम प्राप्त करता है। |
| [getColSpan()](#getColSpan--) | वर्तमान सेल द्वारा कवर किए जाने वाले पैरेंट टेबल की ग्रिड कॉलमों की संख्या लौटाता है। |
| [getRowSpan()](#getRowSpan--) | मर्ज किए गए सेल द्वारा कवर किए जाने वाले पंक्तियों की संख्या लौटाता है। |
| [getTextFrame()](#getTextFrame--) | सेल का टेक्स्ट फ्रेम लौटाता है। |
| [getTable()](#getTable--) | सेल के लिए पैरेंट Table ऑब्जेक्ट लौटाता है। |
| [isMergedCell()](#isMergedCell--) | यदि सेल किसी समायोजित सेल के साथ मर्ज किया गया है तो true लौटाता है, अन्यथा false। |
| [getCellFormat()](#getCellFormat--) | उस CellFormat ऑब्जेक्ट को लौटाता है जिसमें इस सेल के फ़ॉर्मेटिंग प्रॉपर्टीज़ हैं। |
| [splitByColSpan(int index)](#splitByColSpan-int-) | कॉलम अनुक्रमांक द्वारा सेल को दो भागों में विभाजित करता है। |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | पंक्ति अनुक्रमांक द्वारा सेल को दो भागों में विभाजित करता है। |
| [splitByHeight(double height)](#splitByHeight-double-) | ऊँचाई द्वारा सेल को विभाजित करता है। |
| [splitByWidth(double width)](#splitByWidth-double-) | चौड़ाई द्वारा सेल को विभाजित करता है। |
| [getSlide()](#getSlide--) | सेल का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | सेल की पैरेंट प्रेजेंटेशन लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

टेबल की बाएँ पक्ष से सेल के बाएँ पक्ष तक की दूरी लौटाता है। केवल-पढ़ने योग्य double।

**रिटर्न:**  
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

टेबल की शीर्ष पक्ष से सेल के शीर्ष पक्ष तक की दूरी लौटाता है। केवल-पढ़ने योग्य double।

**रिटर्न:**  
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

सेल द्वारा कवर की गई पहली पंक्ति का अनुक्रमांक लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

सेल द्वारा कवर किए गए पहले कॉलम का अनुक्रमांक लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

सेल की चौड़ाई लौटाता है। केवल-पढ़ने योग्य double।

**रिटर्न:**  
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

सेल की ऊँचाई लौटाता है। केवल-पढ़ने योग्य double।

**रिटर्न:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

सेल की न्यूनतम ऊँचाई लौटाता है। यह सेल द्वारा कवर की गई सभी पंक्तियों की न्यूनतम ऊँचाइयों का योग है। केवल-पढ़ने योग्य double।

**रिटर्न:**  
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

टेक्स्टफ़्रेम में बाएँ मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**  
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

टेक्स्टफ़्रेम में बाएँ मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

टेक्स्टफ़्रेम में दाएँ मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**  
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

टेक्स्टफ़्रेम में दाएँ मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

टेक्स्टफ़्रेम में शीर्ष मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**  
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

टेक्स्टफ़्रेम में शीर्ष मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

टेक्स्टफ़्रेम में नीचे मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें double।

**रिटर्न:**  
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

टेक्स्टफ़्रेम में नीचे मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

वर्टिकल टेक्स्ट का प्रकार लौटाता या सेट करता है। पढ़ें/लिखें [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**रिटर्न:**  
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

वर्टिकल टेक्स्ट का प्रकार लौटाता या सेट करता है। पढ़ें/लिखें [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

टेक्स्ट एंकर प्रकार लौटाता या सेट करता है। पढ़ें/लिखें [TextAnchorType](../../com.aspose.slides/textanchortype)।

**रिटर्न:**  
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

टेक्स्ट एंकर प्रकार लौटाता या सेट करता है। पढ़ें/लिखें [TextAnchorType](../../com.aspose.slides/textanchortype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

निर्धारित करता है कि क्या टेक्स्ट बॉक्स सेल के अंदर केंद्रित है। पढ़ें/लिखें boolean।

**रिटर्न:**  
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

निर्धारित करता है कि क्या टेक्स्ट बॉक्स सेल के अंदर केंद्रित है। पढ़ें/लिखें boolean।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

सेल की पहली पंक्ति प्राप्त करता है। केवल-पढ़ने योग्य [IRow](../../com.aspose.slides/irow)।

**रिटर्न:**  
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

सेल का पहला कॉलम प्राप्त करता है। केवल-पढ़ने योग्य [IColumn](../../com.aspose.slides/icolumn)।

**रिटर्न:**  
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

पैरेंट टेबल की ग्रिड कॉलमों में वह संख्या लौटाता है जो वर्तमान सेल द्वारा विस्तारित होगी। यह प्रॉपर्टी सेल को मर्ज किया हुआ दिखाने की अनुमति देती है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

मर्ज किए गए सेल द्वारा कवर की गई पंक्तियों की संख्या लौटाता है। यह vMerge एट्रिब्यूट के साथ प्रयोग किया जाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

सेल का टेक्स्ट फ्रेम लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

सेल के लिए पैरेंट Table ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ITable](../../com.aspose.slides/itable)।

**रिटर्न:**  
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

सही लौटाता है यदि सेल किसी समायोजित सेल के साथ मर्ज किया गया है, अन्यथा गलत। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

उस CellFormat ऑब्जेक्ट को लौटाता है जिसमें इस सेल के फ़ॉर्मेटिंग प्रॉपर्टीज़ हैं। केवल-पढ़ने योग्य [ICellFormat](../../com.aspose.slides/icellformat)।

**रिटर्न:**  
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

कॉलम अनुक्रमांक द्वारा सेल को दो भागों में विभाजित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कॉलम का अनुक्रमांक। |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

पंक्ति अनुक्रमांक द्वारा सेल को दो भागों में विभाजित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | पंक्ति का अनुक्रमांक। |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

ऊँचाई द्वारा सेल को विभाजित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| height | double | पंक्ति की ऊँचाई। |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

चौड़ाई द्वारा सेल को विभाजित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | double | कॉलम की चौड़ाई। |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

सेल का पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**रिटर्न:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

सेल की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**  
com.aspose.slides.IDOMObject