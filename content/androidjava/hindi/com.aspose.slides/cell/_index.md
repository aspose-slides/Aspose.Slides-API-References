---
title: Cell
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: टेबल की एक कक्ष का प्रतिनिधित्व करता है।
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

टेबल की एक कक्ष का प्रतिनिधित्व करता है।
## विधि

| विधि | विवरण |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | टेबल के बाएँ पक्ष से कक्ष के बाएँ पक्ष तक की दूरी लौटाता है। |
| [getOffsetY()](#getOffsetY--) | टेबल के शीर्ष पक्ष से कक्ष के शीर्ष पक्ष तक की दूरी लौटाता है। |
| [getFirstRowIndex()](#getFirstRowIndex--) | कक्ष द्वारा कवर की गई पहली पंक्ति का सूचकांक लौटाता है। |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | कक्ष द्वारा कवर किए गए पहले स्तंभ का सूचकांक लौटाता है। |
| [getWidth()](#getWidth--) | कक्ष की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | कक्ष की ऊँचाई लौटाता है। |
| [getMinimalHeight()](#getMinimalHeight--) | कक्ष की न्यूनतम ऊँचाई लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है। |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है। |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है। |
| [getMarginTop()](#getMarginTop--) | TextFrame में ऊपरी मार्जिन लौटाता है या सेट करता है। |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame में ऊपरी मार्जिन लौटाता है या सेट करता है। |
| [getMarginBottom()](#getMarginBottom--) | TextFrame में नीचे का मार्जिन लौटाता है या सेट करता है। |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame में नीचे का मार्जिन लौटाता है या सेट करता है। |
| [getTextVerticalType()](#getTextVerticalType--) | वर्टिकल टेक्स्ट के प्रकार को लौटाता है या सेट करता है। |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | वर्टिकल टेक्स्ट के प्रकार को लौटाता है या सेट करता है। |
| [getTextAnchorType()](#getTextAnchorType--) | टेक्स्ट एंकर प्रकार को लौटाता है या सेट करता है। |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | टेक्स्ट एंकर प्रकार को लौटाता है या सेट करता है। |
| [getAnchorCenter()](#getAnchorCenter--) | निर्धारित करता है कि टेक्स्ट बॉक्स कक्ष के भीतर केंद्रित है या नहीं। |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | निर्धारित करता है कि टेक्स्ट बॉक्स कक्ष के भीतर केंद्रित है या नहीं। |
| [getFirstRow()](#getFirstRow--) | कक्ष की पहली पंक्ति प्राप्त करता है। |
| [getFirstColumn()](#getFirstColumn--) | कक्ष का पहला स्तंभ प्राप्त करता है। |
| [getColSpan()](#getColSpan--) | पेरेंट टेबल के टेबल ग्रिड में ग्रिड कॉलमों की संख्या लौटाता है जो वर्तमान कक्ष द्वारा विस्तारित होगी। |
| [getRowSpan()](#getRowSpan--) | मर्ज्ड कक्ष द्वारा कवर किए गए पंक्तियों की संख्या लौटाता है। |
| [getTextFrame()](#getTextFrame--) | कक्ष का टेक्स्ट फ़्रेम लौटाता है। |
| [getTable()](#getTable--) | कक्ष के लिए पेरेंट Table ऑब्जेक्ट लौटाता है। |
| [isMergedCell()](#isMergedCell--) | यदि कक्ष किसी भी समायोजित कक्ष के साथ मर्ज्ड है तो true लौटाता है, अन्यथा false। |
| [getCellFormat()](#getCellFormat--) | इस कक्ष के लिए फ़ॉर्मेटिंग प्रॉपर्टीज़ वाला CellFormat ऑब्जेक्ट लौटाता है। |
| [splitByColSpan(int index)](#splitByColSpan-int-) | कॉलम के सूचकांक द्वारा कक्ष को दो कक्षों में विभाजित करता है। |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | पंक्ति के सूचकांक द्वारा कक्ष को दो कक्षों में विभाजित करता है। |
| [splitByHeight(double height)](#splitByHeight-double-) | ऊँचाई द्वारा कक्ष को विभाजित करता है। |
| [splitByWidth(double width)](#splitByWidth-double-) | चौड़ाई द्वारा कक्ष को विभाजित करता है। |
| [getSlide()](#getSlide--) | कक्ष की पेरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | कक्ष की पेरेंट प्रेजेंटेशन लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```


टेबल के बाएँ पक्ष से कक्ष के बाएँ पक्ष तक की दूरी लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```


टेबल के शीर्ष पक्ष से कक्ष के शीर्ष पक्ष तक की दूरी लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```


कक्ष द्वारा कवर की गई पहली पंक्ति का सूचकांक लौटाता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```


कक्ष द्वारा कवर किए गए पहले स्तंभ का सूचकांक लौटाता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


कक्ष की चौड़ाई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```


कक्ष की ऊँचाई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


कक्ष की न्यूनतम ऊँचाई लौटाता है। यह कक्ष द्वारा कवर की गई सभी पंक्तियों की न्यूनतम ऊँचाइयों का योग है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें योग्य double.

**वापसी:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें योग्य double.

**वापसी:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


TextFrame में ऊपरी मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें योग्य double.

**वापसी:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


TextFrame में ऊपरी मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


TextFrame में नीचे का मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें योग्य double.

**वापसी:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


TextFrame में नीचे का मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


वर्टिकल टेक्स्ट के प्रकार को लौटाता या सेट करता है। पढ़ें/लिखें योग्य [TextVerticalType](../../com.aspose.slides/textverticaltype).

**वापसी:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


वर्टिकल टेक्स्ट के प्रकार को लौटाता या सेट करता है। पढ़ें/लिखें योग्य [TextVerticalType](../../com.aspose.slides/textverticaltype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```


टेक्स्ट एंकर प्रकार को लौटाता या सेट करता है। पढ़ें/लिखें योग्य [TextAnchorType](../../com.aspose.slides/textanchortype).

**वापसी:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```


टेक्स्ट एंकर प्रकार को लौटाता या सेट करता है। पढ़ें/लिखें योग्य [TextAnchorType](../../com.aspose.slides/textanchortype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```


निर्धारित करता है कि टेक्स्ट बॉक्स कक्ष के भीतर केंद्रित है या नहीं। पढ़ें/लिखें योग्य boolean.

**वापसी:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```


निर्धारित करता है कि टेक्स्ट बॉक्स कक्ष के भीतर केंद्रित है या नहीं। पढ़ें/लिखें योग्य boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```


कक्ष की पहली पंक्ति प्राप्त करता है। केवल-पढ़ने योग्य [IRow](../../com.aspose.slides/irow).

**वापसी:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```


कक्ष का पहला स्तंभ प्राप्त करता है। केवल-पढ़ने योग्य [IColumn](../../com.aspose.slides/icolumn).

**वापसी:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```


पेरेंट टेबल के टेबल ग्रिड में ग्रिड कॉलमों की संख्या लौटाता है जो वर्तमान कक्ष द्वारा विस्तारित होगी। यह प्रॉपर्टी कक्षों को मर्ज्ड दिखाई देने की अनुमति देती है, क्योंकि वे टेबल में अन्य कक्षों की ऊर्ध्वाधर सीमा को पार करती हैं। केवल-पढ़ने योग्य int.

**वापसी:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```


मर्ज्ड कक्ष द्वारा कवर किए गए पंक्तियों की संख्या लौटाता है। यह अन्य कक्षों पर vMerge एट्रिब्यूट के साथ संयोजन में उपयोग किया जाता है ताकि क्षैतिज मर्ज के आरंभ कक्ष को निर्दिष्ट किया जा सके। केवल-पढ़ने योग्य int.

**वापसी:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


कक्ष का टेक्स्ट फ़्रेम लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe).

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```


कक्ष के लिए पेरेंट Table ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ITable](../../com.aspose.slides/itable).

**वापसी:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```


यदि कक्ष किसी भी समायोजित कक्ष के साथ मर्ज्ड है तो true लौटाता है, अन्यथा false। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```


इस कक्ष के लिए फ़ॉर्मेटिंग प्रॉपर्टीज़ वाला CellFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ICellFormat](../../com.aspose.slides/icellformat).

**वापसी:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```


कॉलम के सूचकांक द्वारा कक्ष को दो कक्षों में विभाजित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कॉलम का सूचकांक। |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```


पंक्ति के सूचकांक द्वारा कक्ष को दो कक्षों में विभाजित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | पंक्ति का सूचकांक। |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```


ऊँचाई द्वारा कक्ष को विभाजित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| height | double | पंक्ति की ऊँचाई। |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```


चौड़ाई द्वारा कक्ष को विभाजित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | double | स्तंभ की चौड़ाई। |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


कक्ष की पेरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide).

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


कक्ष की पेरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject.

**वापसी:**
com.aspose.slides.IDOMObject