---
title: ICell
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक तालिका में सेल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icell/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

टेबल में एक सेल का प्रतिनिधित्व करता है।

## विधियाँ

| Method | Description |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | टेबल के बाएँ पक्ष से सेल के बाएँ पक्ष तक की दूरी लौटाता है। |
| [getOffsetY()](#getOffsetY--) | टेबल के ऊपर पक्ष से सेल के ऊपर पक्ष तक की दूरी लौटाता है। |
| [getFirstRowIndex()](#getFirstRowIndex--) | सेल द्वारा कवर की गई पहली पंक्ति का अनुक्रमांक लौटाता है। |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | सेल द्वारा कवर किए गए पहले कॉलम का अनुक्रमांक लौटाता है। |
| [getWidth()](#getWidth--) | सेल की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | सेल की ऊँचाई लौटाता है। |
| [getMinimalHeight()](#getMinimalHeight--) | सेल की न्यूनतम ऊँचाई लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | TextFrame में बाएँ मार्जिन प्राप्त करता या सेट करता है। |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame में बाएँ मार्जिन प्राप्त करता या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | TextFrame में दाएँ मार्जिन प्राप्त करता या सेट करता है। |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame में दाएँ मार्जिन प्राप्त करता या सेट करता है। |
| [getMarginTop()](#getMarginTop--) | TextFrame में ऊपर मार्जिन प्राप्त करता या सेट करता है। |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame में ऊपर मार्जिन प्राप्त करता या सेट करता है। |
| [getMarginBottom()](#getMarginBottom--) | TextFrame में नीचे मार्जिन प्राप्त करता या सेट करता है। |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame में नीचे मार्जिन प्राप्त करता या सेट करता है। |
| [getTextVerticalType()](#getTextVerticalType--) | वर्टिकल टेक्स्ट का प्रकार प्राप्त करता या सेट करता है। |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | वर्टिकल टेक्स्ट का प्रकार प्राप्त करता या सेट करता है। |
| [getTextAnchorType()](#getTextAnchorType--) | टेक्स्ट एंकर प्रकार प्राप्त करता या सेट करता है। |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | टेक्स्ट एंकर प्रकार प्राप्त करता या सेट करता है। |
| [getAnchorCenter()](#getAnchorCenter--) | निर्धारित करता है कि टेक्स्ट बॉक्स सेल के अंदर केंद्रित है या नहीं। |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | निर्धारित करता है कि टेक्स्ट बॉक्स सेल के अंदर केंद्रित है या नहीं। |
| [getFirstColumn()](#getFirstColumn--) | सेल का पहला कॉलम प्राप्त करता है। |
| [getFirstRow()](#getFirstRow--) | सेल की पहली पंक्ति प्राप्त करता है। |
| [getColSpan()](#getColSpan--) | पैरेंट टेबल के टेबल ग्रिड में उन ग्रिड कॉलमों की संख्या लौटाता है जिन्हें वर्तमान सेल द्वारा विस्तारित किया जाना चाहिए। |
| [getRowSpan()](#getRowSpan--) | एक मर्ज किए गए सेल द्वारा कवर की गई पंक्तियों की संख्या लौटाता है। |
| [getTextFrame()](#getTextFrame--) | सेल का टेक्स्ट फ़्रेम लौटाता है। |
| [getTable()](#getTable--) | सेल के पैरेंट Table ऑब्जेक्ट को लौटाता है। |
| [isMergedCell()](#isMergedCell--) | यदि सेल किसी समायोजित सेल के साथ मर्ज है तो true लौटाता है, अन्यथा false। |
| [getCellFormat()](#getCellFormat--) | CellFormat ऑब्जेक्ट लौटाता है जिसमें इस सेल के फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। |
| [splitByColSpan(int index)](#splitByColSpan-int-) | सेल को कॉलम इंडेक्स के आधार पर दो सेल में विभाजित करता है। |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | सेल को पंक्ति इंडेक्स के आधार पर दो सेल में विभाजित करता है। |
| [splitByHeight(double height)](#splitByHeight-double-) | सेल को ऊँचाई के आधार पर विभाजित करता है। |
| [splitByWidth(double width)](#splitByWidth-double-) | सेल को चौड़ाई के आधार पर विभाजित करता है। |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

टेबल के बाएँ पक्ष से सेल के बाएँ पक्ष तक की दूरी लौटाता है। Read-only double.

**रिटर्न:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

टेबल के ऊपर पक्ष से सेल के ऊपर पक्ष तक की दूरी लौटाता है। Read-only double.

**रिटर्न:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

सेल द्वारा कवर की गई पहली पंक्ति का अनुक्रमांक लौटाता है। Read-only int.

**रिटर्न:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

सेल द्वारा कवर किए गए पहले कॉलम का अनुक्रमांक लौटाता है। Read-only int.

**रिटर्न:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

सेल की चौड़ाई लौटाता है। Read-only double.

**रिटर्न:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

सेल की ऊँचाई लौटाता है। Read-only double.

**रिटर्न:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

सेल की न्यूनतम ऊँचाई लौटाता है। यह सभी पंक्तियों की न्यूनतम ऊँचाइयों का योग है जो सेल द्वारा कवर की गई हैं। Read-only double.

**रिटर्न:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame में बाएँ मार्जिन प्राप्त करता या सेट करता है। Read/write double.

**रिटर्न:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

TextFrame में बाएँ मार्जिन प्राप्त करता या सेट करता है। Read/write double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame में दाएँ मार्जिन प्राप्त करता या सेट करता है। Read/write double.

**रिटर्न:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

TextFrame में दाएँ मार्जिन प्राप्त करता या सेट करता है। Read/write double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame में ऊपर मार्जिन प्राप्त करता या सेट करता है। Read/write double.

**रिटर्न:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

TextFrame में ऊपर मार्जिन प्राप्त करता या सेट करता है। Read/write double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame में नीचे मार्जिन प्राप्त करता या सेट करता है। Read/write double.

**रिटर्न:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

TextFrame में नीचे मार्जिन प्राप्त करता या सेट करता है। Read/write double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

वर्टिकल टेक्स्ट का प्रकार प्राप्त करता या सेट करता है। Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**रिटर्न:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

वर्टिकल टेक्स्ट का प्रकार प्राप्त करता या सेट करता है। Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

टेक्स्ट एंकर प्रकार प्राप्त करता या सेट करता है। Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**रिटर्न:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

टेक्स्ट एंकर प्रकार प्राप्त करता या सेट करता है। Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

निर्धारित करता है कि टेक्स्ट बॉक्स सेल के अंदर केंद्रित है या नहीं। Read/write boolean.

**रिटर्न:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

निर्धारित करता है कि टेक्स्ट बॉक्स सेल के अंदर केंद्रित है या नहीं। Read/write boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

सेल का पहला कॉलम प्राप्त करता है। Read-only [IColumn](../../com.aspose.slides/icolumn).

**रिटर्न:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

सेल की पहली पंक्ति प्राप्त करता है। Read-only [IRow](../../com.aspose.slides/irow).

**रिटर्न:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

पैरेंट टेबल के टेबल ग्रिड में उन ग्रिड कॉलमों की संख्या लौटाता है जिन्हें वर्तमान सेल द्वारा विस्तारित किया जाना चाहिए। यह प्रॉपर्टी सेल को मर्ज किए गए दिखाने की अनुमति देती है, क्योंकि वे टेबल में अन्य सेलों की वर्टिकल सीमाओं को कवर करते हैं। Read-only int.

**रिटर्न:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

एक मर्ज किए गए सेल द्वारा कवर की गई पंक्तियों की संख्या लौटाता है। यह अन्य सेलों में vMerge एट्रिब्यूट के साथ उपयोग किया जाता है ताकि क्षैतिज मर्ज की शुरुआत सेल निर्दिष्ट की जा सके। Read-only int.

**रिटर्न:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

सेल का टेक्स्ट फ़्रेम लौटाता है। Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

सेल के पैरेंट Table ऑब्जेक्ट को लौटाता है। Read-only [ITable](../../com.aspose.slides/itable).

**रिटर्न:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

यदि सेल किसी समायोजित सेल के साथ मर्ज है तो true लौटाता है, अन्यथा false। Read-only boolean.

**रिटर्न:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

CellFormat ऑब्जेक्ट लौटाता है जिसमें इस सेल के फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। Read-only [ICellFormat](../../com.aspose.slides/icellformat).

**रिटर्न:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

सेल को कॉलम इंडेक्स के आधार पर दो सेल में विभाजित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कॉलम का इंडेक्स। |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

सेल को पंक्ति इंडेक्स के आधार पर दो सेल में विभाजित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | पंक्ति का इंडेक्स। |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

सेल को ऊँचाई के आधार पर विभाजित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| height | double | पंक्ति की ऊँचाई। |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

सेल को चौड़ाई के आधार पर विभाजित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | double | कॉलम की चौड़ाई। |