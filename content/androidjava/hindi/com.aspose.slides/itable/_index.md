---
title: ITable
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक स्लाइड पर तालिका का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/itable/
---
**सभी लागू इंटरफेस:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

स्लाइड पर तालिका का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | निर्दिष्ट कॉलम और पंक्ति अनुक्रमांक पर स्थित सेल को लौटाता है। |
| [getRows()](#getRows--) | पंक्तियों का संग्रह लौटाता है। |
| [getColumns()](#getColumns--) | कॉलमों का संग्रह लौटाता है। |
| [getTableFormat()](#getTableFormat--) | TableFormat वस्तु जो इस तालिका के फ़ॉर्मेटिंग गुणों को समाहित करती है, लौटाता है। |
| [getStylePreset()](#getStylePreset--) | निर्मित तालिका शैली को प्राप्त करता है या सेट करता है। |
| [setStylePreset(int value)](#setStylePreset-int-) | निर्मित तालिका शैली को प्राप्त करता है या सेट करता है। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि क्या तालिका का दाएँ-से-बाएँ पढ़ने क्रम है। |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | निर्धारित करता है कि क्या तालिका का दाएँ-से-बाएँ पढ़ने क्रम है। |
| [getFirstRow()](#getFirstRow--) | निर्धारित करता है कि क्या तालिका की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | निर्धारित करता है कि क्या तालिका की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [getFirstCol()](#getFirstCol--) | निर्धारित करता है कि क्या तालिका के पहले कॉलम को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | निर्धारित करता है कि क्या तालिका के पहले कॉलम को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [getLastRow()](#getLastRow--) | निर्धारित करता है कि क्या तालिका की आखिरी पंक्ति को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [setLastRow(boolean value)](#setLastRow-boolean-) | निर्धारित करता है कि क्या तालिका की आखिरी पंक्ति को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [getLastCol()](#getLastCol--) | निर्धारित करता है कि क्या तालिका का आखिरी कॉलम विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [setLastCol(boolean value)](#setLastCol-boolean-) | निर्धारित करता है कि क्या तालिका का आखिरी कॉलम विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [getHorizontalBanding()](#getHorizontalBanding--) | निर्धारित करता है कि क्या सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | निर्धारित करता है कि क्या सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [getVerticalBanding()](#getVerticalBanding--) | निर्धारित करता है कि क्या सम कॉलमों को अलग फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | निर्धारित करता है कि क्या सम कॉलमों को अलग फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | सन्निकट कोशिकाओं को मिलाता है। |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```


निर्दिष्ट कॉलम और पंक्ति अनुक्रमांक पर स्थित सेल को लौटाता है। केवल-पढ़ने योग्य [ICell](../../com.aspose.slides/icell)।

**परामीटर:**
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


कॉलमों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IColumnCollection](../../com.aspose.slides/icolumncollection)।

**रिटर्न:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```


TableFormat वस्तु जो इस तालिका के फ़ॉर्मेटिंग गुणों को समाहित करती है, लौटाता है। केवल-पढ़ने योग्य [ITableFormat](../../com.aspose.slides/itableformat)।

**रिटर्न:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```


निर्मित तालिका शैली को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य [TableStylePreset](../../com.aspose.slides/tablestylepreset)।

**रिटर्न:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```


निर्मित तालिका शैली को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य [TableStylePreset](../../com.aspose.slides/tablestylepreset)।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


निर्धारित करता है कि क्या तालिका का दाएँ-से-बाएँ पढ़ने क्रम है। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```


निर्धारित करता है कि क्या तालिका का दाएँ-से-बाएँ पढ़ने क्रम है। पढ़ने-लिखने योग्य boolean।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```


निर्धारित करता है कि क्या तालिका की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```


निर्धारित करता है कि क्या तालिका की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```


निर्धारित करता है कि क्या तालिका का पहला कॉलम विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```


निर्धारित करता है कि क्या तालिका का पहला कॉलम विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```


निर्धारित करता है कि क्या तालिका की आखिरी पंक्ति को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```


निर्धारित करता है कि क्या तालिका की आखिरी पंक्ति को विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```


निर्धारित करता है कि क्या तालिका का आखिरी कॉलम विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```


निर्धारित करता है कि क्या तालिका का आखिरी कॉलम विशेष फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```


निर्धारित करता है कि क्या सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```


निर्धारित करता है कि क्या सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```


निर्धारित करता है कि क्या सम कॉलमों को अलग फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**रिटर्न:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```


निर्धारित करता है कि क्या सम कॉलमों को अलग फ़ॉर्मेटिंग के साथ तैयार किया जाना चाहिए। पढ़ने-लिखने योग्य boolean।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


सन्निकट कोशिकाओं को मिलाता है।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | मिलाने के लिये सेल। |
| cell2 | [ICell](../../com.aspose.slides/icell) | मिलाने के लिये सेल। |
| allowSplitting | boolean | विभाजन की अनुमति के लिये true। |

**रिटर्न:**
[ICell](../../com.aspose.slides/icell) - मिलाया गया सेल।