---
title: Table
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक स्लाइड पर टेबल का प्रतिनिधित्व करता है।
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

एक स्लाइड पर टेबल का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | निर्दिष्ट कॉलम और पंक्ति अनुक्रमणियों पर सेल लौटाता है। |
| [getRows()](#getRows--) | पंक्तियों का संग्रह लौटाता है। |
| [getColumns()](#getColumns--) | कॉलम का संग्रह लौटाता है। |
| [getTableFormat()](#getTableFormat--) | इस टेबल के फ़ॉर्मेटिंग गुणों को शामिल करने वाले TableFormat ऑब्जेक्ट को लौटाता है। |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | आस पास के सेल्स को मिलाता है। |
| [getStylePreset()](#getStylePreset--) | निर्मित टेबल स्टाइल को प्राप्त या निर्धारित करता है। |
| [setStylePreset(int value)](#setStylePreset-int-) | निर्मित टेबल स्टाइल को प्राप्त या निर्धारित करता है। |
| [getRightToLeft()](#getRightToLeft--) | निर्धारित करता है कि टेबल दाएं से बाएं पढ़ने के क्रम में है या नहीं। |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | निर्धारित करता है कि टेबल दाएं से बाएं पढ़ने के क्रम में है या नहीं। |
| [getFirstRow()](#getFirstRow--) | निर्धारित करता है कि टेबल की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | निर्धारित करता है कि टेबल की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [getFirstCol()](#getFirstCol--) | निर्धारित करता है कि टेबल के पहले कॉलम को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | निर्धारित करता है कि टेबल के पहले कॉलम को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [getLastRow()](#getLastRow--) | निर्धारित करता है कि टेबल की अंतिम पंक्ति को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [setLastRow(boolean value)](#setLastRow-boolean-) | निर्धारित करता है कि टेबल की अंतिम पंक्ति को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [getLastCol()](#getLastCol--) | निर्धारित करता है कि टेबल के अंतिम कॉलम को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [setLastCol(boolean value)](#setLastCol-boolean-) | निर्धारित करता है कि टेबल के अंतिम कॉलम को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [getHorizontalBanding()](#getHorizontalBanding--) | निर्धारित करता है कि सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | निर्धारित करता है कि सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [getVerticalBanding()](#getVerticalBanding--) | निर्धारित करता है कि सम कॉलम को अलग फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | निर्धारित करता है कि सम कॉलम को अलग फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | सभी टेबल सेल्स के भागों पर निर्धारित पोर्शन फ़ॉर्मेट गुण सेट करता है। |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | सभी टेबल सेल्स के पैराग्राफ़ पर निर्धारित पैराग्राफ़ फ़ॉर्मेट गुण सेट करता है। |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | सभी टेबल सेल्स के टेक्स्ट फ़्रेम पर निर्धारित टेक्स्ट फ़्रेम फ़ॉर्मेट गुण सेट करता है। |
| [getFillFormat()](#getFillFormat--) | टेबल के लिए भराव फ़ॉर्मेटिंग को शामिल करने वाला TableFormat.FillFormat ऑब्जेक्ट लौटाता है। |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

निर्दिष्ट कॉलम और पंक्ति अनुक्रमणियों पर सेल लौटाता है। केवल-पढ़ने योग्य [Cell](../../com.aspose.slides/cell).

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**वापसी:**  
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

पंक्तियों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IRowCollection](../../com.aspose.slides/irowcollection).

**वापसी:**  
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

कॉलम का संग्रह लौटाता है। केवल-पढ़ने योग्य [IColumnCollection](../../com.aspose.slides/icolumncollection).

**वापसी:**  
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

इस टेबल के फ़ॉर्मेटिंग गुणों को शामिल करने वाले TableFormat ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [ITableFormat](../../com.aspose.slides/itableformat).

**वापसी:**  
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

आस पास के सेल्स को मिलाता है।

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | मर्ज करने के लिये सेल। |
| cell2 | [ICell](../../com.aspose.slides/icell) | मर्ज करने के लिये सेल। |
| allowSplitting | boolean | सेल विभाजन की अनुमति देने के लिये true। |

**वापसी:**  
[ICell](../../com.aspose.slides/icell) - मिलाया गया सेल।

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

निर्मित टेबल स्टाइल को प्राप्त या निर्धारित करता है। पढ़ने/लिखने योग्य [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**वापसी:**  
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

निर्मित टेबल स्टाइल को प्राप्त या निर्धारित करता है। पढ़ने/लिखने योग्य [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

निर्धारित करता है कि टेबल दाएं से बाएं पढ़ने के क्रम में है या नहीं। पढ़ने/लिखने योग्य  boolean .

**वापसी:**  
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

निर्धारित करता है कि टेबल दाएं से बाएं पढ़ने के क्रम में है या नहीं। पढ़ने/लिखने योग्य  boolean .

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

निर्धारित करता है कि टेबल की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**वापसी:**  
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

निर्धारित करता है कि टेबल की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

निर्धारित करता है कि टेबल के पहले कॉलम को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**वापसी:**  
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

निर्धारित करता है कि टेबल के पहले कॉलम को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**परामीटर**  
| परامیटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

निर्धारित करता है कि टेबल की अंतिम पंक्ति को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**वापसी:**  
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

निर्धारित करता है कि टेबल की अंतिम पंक्ति को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

निर्धारित करता है कि टेबल के अंतिम कॉलम को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**वापसी:**  
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

निर्धारित करता है कि टेबल के अंतिम कॉलम को विशेष फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

निर्धारित करता है कि सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**वापसी:**  
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

निर्धारित करता है कि सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

निर्धारित करता है कि सम कॉलम को अलग फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**वापसी:**  
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

निर्धारित करता है कि सम कॉलम को अलग फ़ॉर्मेटिंग के साथ बनाया जाए या नहीं। पढ़ने/लिखने योग्य  boolean .

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

सभी टेबल सेल्स के भागों पर निर्धारित पोर्शन फ़ॉर्मेट गुण सेट करता है।

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | आवश्यक गुण सेट किए हुए IPortionFormat ऑब्जेक्ट। |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

सभी टेबल सेल्स के पैराग्राफ़ पर निर्धारित पैराग्राफ़ फ़ॉर्मेट गुण सेट करता है।

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | आवश्यक गुण सेट किए हुए IParagraphFormat ऑब्जेक्ट। |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

सभी टेबल सेल्स के टेक्स्ट फ़्रेम पर निर्धारित टेक्स्ट फ़्रेम फ़ॉर्मेट गुण सेट करता है।

**परामीटर**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | आवश्यक गुण सेट किए हुए ITextFrameFormat ऑब्जेक्ट। |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

टेबल के लिए भराव फ़ॉर्मेटिंग को शामिल करने वाला TableFormat.FillFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**वापसी:**  
[IFillFormat](../../com.aspose.slides/ifillformat)