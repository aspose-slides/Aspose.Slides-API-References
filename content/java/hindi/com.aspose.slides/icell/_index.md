---
title: ICell
second_title: Aspose.Slides for Java API संदर्भ
description: एक तालिका में एक सेल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icell/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

एक तालिका में एक सेल का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | एक तालिका के बाएँ पक्ष से सेल के बाएँ पक्ष तक की दूरी लौटाता है। |
| [getOffsetY()](#getOffsetY--) | एक तालिका के ऊपरी पक्ष से सेल के ऊपरी पक्ष तक की दूरी लौटाता है। |
| [getFirstRowIndex()](#getFirstRowIndex--) | सेल द्वारा कवर की गई पहली पंक्ति का सूचकांक लौटाता है। |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | सेल द्वारा कवर किए गए पहले कॉलम का सूचकांक लौटाता है। |
| [getWidth()](#getWidth--) | सेल की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | सेल की ऊँचाई लौटाता है। |
| [getMinimalHeight()](#getMinimalHeight--) | सेल की न्यूनतम ऊँचाई लौटाता है। |
| [getMarginLeft()](#getMarginLeft--) | TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है। |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है। |
| [getMarginRight()](#getMarginRight--) | TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है। |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है। |
| [getMarginTop()](#getMarginTop--) | TextFrame में ऊपर का मार्जिन लौटाता है या सेट करता है। |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame में ऊपर का मार्जिन लौटाता है या सेट करता है। |
| [getMarginBottom()](#getMarginBottom--) | TextFrame में नीचे का मार्जिन लौटाता है या सेट करता है। |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame में नीचे का मार्जिन लौटाता है या सेट करता है। |
| [getTextVerticalType()](#getTextVerticalType--) | वर्टिकल टेक्स्ट का प्रकार लौटाता है या सेट करता है। |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | वर्टिकल टेक्स्ट का प्रकार लौटाता है या सेट करता है। |
| [getTextAnchorType()](#getTextAnchorType--) | टेक्स्ट एंकर प्रकार लौटाता है या सेट करता है। |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | टेक्स्ट एंकर प्रकार लौटाता है या सेट करता है। |
| [getAnchorCenter()](#getAnchorCenter--) | निर्धारित करता है कि टेक्स्ट बॉक्स सेल के भीतर केंद्रित है या नहीं। |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | निर्धारित करता है कि टेक्स्ट बॉक्स सेल के भीतर केंद्रित है या नहीं। |
| [getFirstColumn()](#getFirstColumn--) | सेल का पहला कॉलम प्राप्त करता है। |
| [getFirstRow()](#getFirstRow--) | सेल की पहली पंक्ति प्राप्त करता है। |
| [getColSpan()](#getColSpan--) | वर्तमान सेल द्वारा पैरेंट टेबल के ग्रिड में कवर किए जाने वाले ग्रिड कॉलमों की संख्या लौटाता है। |
| [getRowSpan()](#getRowSpan--) | मर्ज्ड सेल द्वारा कवर की गई पंक्तियों की संख्या लौटाता है। |
| [getTextFrame()](#getTextFrame--) | सेल का टेक्स्ट फ्रेम लौटाता है। |
| [getTable()](#getTable--) | सेल के पैरेंट Table ऑब्जेक्ट को लौटाता है। |
| [isMergedCell()](#isMergedCell--) | यदि सेल किसी समायोजित सेल के साथ मर्ज्ड है तो true लौटाता है, अन्यथा false। |
| [getCellFormat()](#getCellFormat--) | वह CellFormat ऑब्जेक्ट लौटाता है जिसमें इस सेल के फ़ॉर्मेटिंग प्रॉपर्टी शामिल हैं। |
| [splitByColSpan(int index)](#splitByColSpan-int-) | कॉलम के इंडेक्स द्वारा सेल को दो भागों में विभाजित करता है। |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | पंक्ति के इंडेक्स द्वारा सेल को दो भागों में विभाजित करता है। |
| [splitByHeight(double height)](#splitByHeight-double-) | ऊँचाई द्वारा सेल को विभाजित करता है। |
| [splitByWidth(double width)](#splitByWidth-double-) | चौड़ाई द्वारा सेल को विभाजित करता है। |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```


एक तालिका के बाएँ पक्ष से सेल के बाएँ पक्ष तक की दूरी लौटाता है। केवल पढ़ने योग्य डबल।

**रिटर्न:**  
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```


एक तालिका के ऊपरी पक्ष से सेल के ऊपरी पक्ष तक की दूरी लौटाता है। केवल पढ़ने योग्य डबल।

**रिटर्न:**  
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```


सेल द्वारा कवर की गई पहली पंक्ति का सूचकांक लौटाता है। केवल पढ़ने योग्य इंट।

**रिटर्न:**  
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```


सेल द्वारा कवर किए गए पहले कॉलम का सूचकांक लौटाता है। केवल पढ़ने योग्य इंट।

**रिटर्न:**  
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


सेल की चौड़ाई लौटाता है। केवल पढ़ने योग्य डबल।

**रिटर्न:**  
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


सेल की ऊँचाई लौटाता है। केवल पढ़ने योग्य डबल।

**रिटर्न:**  
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


सेल की न्यूनतम ऊँचाई लौटाता है। यह सभी पंक्तियों की न्यूनतम ऊँचाइयों का योग है जो सेल द्वारा कवर की गई हैं। केवल पढ़ने योग्य डबल।

**रिटर्न:**  
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है। पढ़ने/लिखने योग्य डबल।

**रिटर्न:**  
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


TextFrame में बायाँ मार्जिन लौटाता है या सेट करता है। पढ़ने/लिखने योग्य डबल।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है। पढ़ने/लिखने योग्य डबल।

**रिटर्न:**  
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


TextFrame में दायाँ मार्जिन लौटाता है या सेट करता है। पढ़ने/लिखने योग्य डबल।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


TextFrame में ऊपर का मार्जिन लौटाता है या सेट करता है। पढ़ने/लिखने योग्य डबल।

**रिटर्न:**  
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


TextFrame में ऊपर का मार्जिन लौटाता है या सेट करता है। पढ़ने/लिखने योग्य डबल।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


TextFrame में नीचे का मार्जिन लौटाता है या सेट करता है। पढ़ने/लिखने योग्य डबल।

**रिटर्न:**  
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


TextFrame में नीचे का मार्जिन लौटाता है या सेट करता है। पढ़ने/लिखने योग्य डबल।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


वर्टिकल टेक्स्ट का प्रकार लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**रिटर्न:**  
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


वर्टिकल टेक्स्ट का प्रकार लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [TextVerticalType](../../com.aspose.slides/textverticaltype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```


टेक्स्ट एंकर प्रकार लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [TextAnchorType](../../com.aspose.slides/textanchortype)।

**रिटर्न:**  
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```


टेक्स्ट एंकर प्रकार लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [TextAnchorType](../../com.aspose.slides/textanchortype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```


निर्धारित करता है कि टेक्स्ट बॉक्स सेल के भीतर केंद्रित है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```


निर्धारित करता है कि टेक्स्ट बॉक्स सेल के भीतर केंद्रित है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```


सेल का पहला कॉलम प्राप्त करता है। केवल पढ़ने योग्य [IColumn](../../com.aspose.slides/icolumn)।

**रिटर्न:**  
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```


सेल की पहली पंक्ति प्राप्त करता है। केवल पढ़ने योग्य [IRow](../../com.aspose.slides/irow)।

**रिटर्न:**  
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```


पैरेंट टेबल की ग्रिड में उन ग्रिड कॉलमों की संख्या लौटाता है जो वर्तमान सेल द्वारा स्पैन किए जाएंगे। यह प्रॉपर्टी सेलों को मर्ज्ड दिखाने की अनुमति देती है, क्योंकि वे टेबल में अन्य सेलों की लंबवत सीमाओं को पार करते हैं। केवल पढ़ने योग्य इंट।

**रिटर्न:**  
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```


मर्ज्ड सेल द्वारा कवर की गई पंक्तियों की संख्या लौटाता है। यह अन्य सेलों पर vMerge एट्रिब्यूट के साथ संयोजन में उपयोग होता है ताकि क्षैतिज मर्ज की शुरूआती सेल निर्दिष्ट की जा सके। केवल पढ़ने योग्य इंट।

**रिटर्न:**  
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


सेल का टेक्स्ट फ्रेम लौटाता है। केवल पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```


सेल के पैरेंट Table ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [ITable](../../com.aspose.slides/itable)।

**रिटर्न:**  
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```


यदि सेल किसी समायोजित सेल के साथ मर्ज्ड है तो true लौटाता है, अन्यथा false। केवल पढ़ने योग्य बूलियन।

**रिटर्न:**  
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```


उस CellFormat ऑब्जेक्ट को लौटाता है जिसमें इस सेल के फ़ॉर्मेटिंग प्रॉपर्टी शामिल हैं। केवल पढ़ने योग्य [ICellFormat](../../com.aspose.slides/icellformat)।

**रिटर्न:**  
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```


कॉलम के इंडेक्स द्वारा सेल को दो भागों में विभाजित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कॉलम का इंडेक्स। |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```


पंक्ति के इंडेक्स द्वारा सेल को दो भागों में विभाजित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | पंक्ति का इंडेक्स। |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```


ऊँचाई द्वारा सेल को विभाजित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| height | double | पंक्ति की ऊँचाई। |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```


चौड़ाई द्वारा सेल को विभाजित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | double | कॉलम की चौड़ाई। |