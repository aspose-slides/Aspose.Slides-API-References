---
title: ITable
second_title: Aspose.Slides के लिए Java API संदर्भ
description: स्लाइड पर एक तालिका का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itable/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

एक स्लाइड पर तालिका को दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | निर्दिष्ट स्तंभ और पंक्ति अनुक्रमणिकाओं पर सेल लौटाता है। |
| [getRows()](#getRows--) | पंक्तियों का संग्रह लौटाता है। |
| [getColumns()](#getColumns--) | स्तंभों का संग्रह लौटाता है। |
| [getTableFormat()](#getTableFormat--) | इस तालिका के लिए स्वरूपण गुणों वाला TableFormat ऑब्जेक्ट लौटाता है। |
| [getStylePreset()](#getStylePreset--) | बिल्ट-इन तालिका शैली को प्राप्त या सेट करता है। |
| [setStylePreset(int value)](#setStylePreset-int-) | बिल्ट-इन तालिका शैली को प्राप्त या सेट करता है। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि तालिका दाएँ-से-बाएँ क्रम में पढ़ी जाती है या नहीं। |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | निर्धारित करता है कि तालिका दाएँ-से-बाएँ क्रम में पढ़ी जाती है या नहीं। |
| [getFirstRow()](#getFirstRow--) | निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [getFirstCol()](#getFirstCol--) | निर्धारित करता है कि तालिका की पहली स्तम्भ को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | निर्धारित करता है कि तालिका की पहली स्तम्भ को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [getLastRow()](#getLastRow--) | निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [setLastRow(boolean value)](#setLastRow-boolean-) | निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [getLastCol()](#getLastCol--) | निर्धारित करता है कि तालिका की अंतिम स्तम्भ को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [setLastCol(boolean value)](#setLastCol-boolean-) | निर्धारित करता है कि तालिका की अंतिम स्तम्भ को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [getHorizontalBanding()](#getHorizontalBanding--) | निर्धारित करता है कि सम पंक्तियों को अलग स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | निर्धारित करता है कि सम पंक्तियों को अलग स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [getVerticalBanding()](#getVerticalBanding--) | निर्धारित करता है कि सम स्तम्भों को अलग स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | निर्धारित करता है कि सम स्तम्भों को अलग स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | समान पड़ोसी सेल को मिलाता है। |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

निर्दिष्ट स्तंभ और पंक्ति अनुक्रमणिकाओं पर सेल लौटाता है। केवल-पढ़ने योग्य [ICell](../../com.aspose.slides/icell).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**रिटर्न:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

पंक्तियों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IRowCollection](../../com.aspose.slides/irowcollection)।

**रिटर्न:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

स्तंभों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IColumnCollection](../../com.aspose.slides/icolumncollection)।

**रिटर्न:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

इस तालिका के लिए स्वरूपण गुणों वाला TableFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ITableFormat](../../com.aspose.slides/itableformat)।

**रिटर्न:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

बिल्ट-इन तालिका शैली को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [TableStylePreset](../../com.aspose.slides/tablestylepreset)।

**रिटर्न:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

बिल्ट-इन तालिका शैली को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [TableStylePreset](../../com.aspose.slides/tablestylepreset)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

निर्धारित करता है कि तालिका दाएँ-से-बाएँ क्रम में पढ़ी जाती है या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

निर्धारित करता है कि तालिका दाएँ-से-बाएँ क्रम में पढ़ी जाती है या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

निर्धारित करता है कि तालिका की पहली स्तम्भ को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

निर्धारित करता है कि तालिका की पहली स्तम्भ को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

निर्धारित करता है कि तालिका की अंतिम स्तम्भ को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

निर्धारित करता है कि तालिका की अंतिम स्तम्भ को विशेष स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

निर्धारित करता है कि सम पंक्तियों को अलग स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

निर्धारित करता है कि सम पंक्तियों को अलग स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

निर्धारित करता है कि सम स्तम्भों को अलग स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

निर्धारित करता है कि सम स्तम्भों को अलग स्वरूपण के साथ दर्शाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

समान पड़ोसी सेल को मिलाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | मिलाने के लिये सेल। |
| cell2 | [ICell](../../com.aspose.slides/icell) | मिलाने के लिये सेल। |
| allowSplitting | boolean | सेल विभाजन की अनुमति के लिये true। |

**रिटर्न:**
[ICell](../../com.aspose.slides/icell) - मर्ज किया गया सेल।