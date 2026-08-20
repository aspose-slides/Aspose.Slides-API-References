---
title: Table
second_title: Aspose.Slides for Java API संदर्भ
description: एक स्लाइड पर तालिका का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/table/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ITable](../../com.aspose.slides/itable)  
```
public final class Table extends GraphicalObject implements ITable
```

एक स्लाइड पर तालिका का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | निर्दिष्ट कॉलम और पंक्ति अनुक्रमणिकाओं पर सेल लौटाता है। |
| [getRows()](#getRows--) | पंक्तियों का संग्रह लौटाता है। |
| [getColumns()](#getColumns--) | स्तंभों का संग्रह लौटाता है। |
| [getTableFormat()](#getTableFormat--) | एक TableFormat ऑब्जेक्ट लौटाता है जिसमें इस तालिका के लिए स्वरूपण गुण होते हैं। |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | पड़ोसी कोशिकाओं को मिलाता है। |
| [getStylePreset()](#getStylePreset--) | निर्मित तालिका शैली को प्राप्त या सेट करता है। |
| [setStylePreset(int value)](#setStylePreset-int-) | निर्मित तालिका शैली को प्राप्त या सेट करता है। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि तालिका दाएँ-से-बाएँ पढ़ने क्रम रखती है या नहीं। |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | निर्धारित करता है कि तालिका दाएँ-से-बाएँ पढ़ने क्रम रखती है या नहीं। |
| [getFirstRow()](#getFirstRow--) | निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [getFirstCol()](#getFirstCol--) | निर्धारित करता है कि तालिका का पहला स्तंभ विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | निर्धारित करता है कि तालिका का पहला स्तंभ विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [getLastRow()](#getLastRow--) | निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [setLastRow(boolean value)](#setLastRow-boolean-) | निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [getLastCol()](#getLastCol--) | निर्धारित करता है कि तालिका का अंतिम स्तंभ विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [setLastCol(boolean value)](#setLastCol-boolean-) | निर्धारित करता है कि तालिका का अंतिम स्तंभ विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [getHorizontalBanding()](#getHorizontalBanding--) | निर्धारित करता है कि सम पंक्तियों को अलग स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | निर्धारित करता है कि सम पंक्तियों को अलग स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [getVerticalBanding()](#getVerticalBanding--) | निर्धारित करता है कि सम स्तंभों को अलग स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | निर्धारित करता है कि सम स्तंभों को अलग स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | सभी तालिका कोशिकाओं के हिस्सों में परिभाषित भाग स्वरूप गुण सेट करता है। |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | सभी तालिका कोशिकाओं के अनुच्छेदों में परिभाषित अनुच्छेद स्वरूप गुण सेट करता है। |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | सभी तालिका कोशिकाओं के टेक्स्ट फ्रेम में परिभाषित टेक्स्ट फ्रेम स्वरूप गुण सेट करता है। |
| [getFillFormat()](#getFillFormat--) | एक TableFormat.FillFormat ऑब्जेक्ट लौटाता है जिसमें तालिका के लिए भराव स्वरूपण होता है। |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

निर्दिष्ट कॉलम और पंक्ति अनुक्रमणिकाओं पर सेल लौटाता है। केवल पढ़ने योग्य [Cell](../../com.aspose.slides/cell).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**वापसी मान:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

पंक्तियों का संग्रह लौटाता है। केवल पढ़ने योग्य [IRowCollection](../../com.aspose.slides/irowcollection).

**वापसी मान:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

स्तंभों का संग्रह लौटाता है। केवल पढ़ने योग्य [IColumnCollection](../../com.aspose.slides/icolumncollection).

**वापसी मान:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

एक TableFormat ऑब्जेक्ट लौटाता है जिसमें इस तालिका के लिए स्वरूपण गुण होते हैं। केवल पढ़ने योग्य [ITableFormat](../../com.aspose.slides/itableformat).

**वापसी मान:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

पड़ोसी कोशिकाओं को मिलाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | मर्ज करने के लिए सेल। |
| cell2 | [ICell](../../com.aspose.slides/icell) | मर्ज करने के लिए सेल। |
| allowSplitting | boolean | सेल विभाजन की अनुमति देने के लिए True। |

**वापसी मान:**
[ICell](../../com.aspose.slides/icell) - मर्ज किया गया सेल।

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

निर्मित तालिका शैली को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**वापसी मान:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

निर्मित तालिका शैली को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

निर्धारित करता है कि तालिका दाएँ-से-बाएँ पढ़ने क्रम रखती है या नहीं। पढ़ने/लिखने योग्य boolean .

**वापसी मान:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

निर्धारित करता है कि तालिका दाएँ-से-बाएँ पढ़ने क्रम रखती है या नहीं। पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**वापसी मान:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

निर्धारित करता है कि तालिका की पहली पंक्ति को विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

निर्धारित करता है कि तालिका का पहला स्तंभ विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**वापसी मान:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

निर्धारित करता है कि तालिका का पहला स्तंभ विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**वापसी मान:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

निर्धारित करता है कि तालिका की अंतिम पंक्ति को विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

निर्धारित करता है कि तालिका का अंतिम स्तंभ विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**वापसी मान:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

निर्धारित करता है कि तालिका का अंतिम स्तंभ विशेष स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

निर्धारित करता है कि सम पंक्तियों को अलग स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**वापसी मान:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

निर्धारित करता है कि सम पंक्तियों को अलग स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

निर्धारित करता है कि सम स्तंभों को अलग स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**वापसी मान:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

निर्धारित करता है कि सम स्तंभों को अलग स्वरूपण के साथ चित्रित किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

सभी तालिका कोशिकाओं के हिस्सों में परिभाषित भाग स्वरूप गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | आवश्यक गुण सेट किए गए IPortionFormat ऑब्जेक्ट। |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

सभी तालिका कोशिकाओं के अनुच्छेदों में परिभाषित अनुच्छेद स्वरूप गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | आवश्यक गुण सेट किए गए IParagraphFormat ऑब्जेक्ट। |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

सभी तालिका कोशिकाओं के टेक्स्ट फ्रेम में परिभाषित टेक्स्ट फ्रेम स्वरूप गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | आवश्यक गुण सेट किए गए ITextFrameFormat ऑब्जेक्ट। |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

एक TableFormat.FillFormat ऑब्जेक्ट लौटाता है जिसमें तालिका के लिए भराव स्वरूपण होता है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**वापसी मान:**
[IFillFormat](../../com.aspose.slides/ifillformat)