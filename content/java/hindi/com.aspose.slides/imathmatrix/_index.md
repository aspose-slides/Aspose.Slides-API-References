---
title: IMathMatrix
second_title: Aspose.Slides for Java API संदर्भ
description: मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है जिसमें एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित बच्चा तत्व होते हैं।
type: docs
url: /hi/com.aspose.slides/imathmatrix/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Matrix वस्तु को निर्दिष्ट करता है, जिसमें एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित बच्चा तत्व होते हैं। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में निर्मित विभाजक नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको विभाजक वस्तु (IMathDelimiter) का उपयोग करना चाहिए। शून्य तर्कों का प्रयोग करके मैट्रिक्स में अंतराल बनाए जा सकते हैं।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | मैट्रिक्स के तत्व |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | मैट्रिक्स के तत्व |
| [getRowCount()](#getRowCount--) | मैट्रिक्स में पंक्तियों की संख्या |
| [getColumnCount()](#getColumnCount--) | मैट्रिक्स में स्तम्भों की संख्या |
| [getHidePlaceholders()](#getHidePlaceholders--) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ डिफ़ॉल्ट: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ डिफ़ॉल्ट: false |
| [getBaseJustification()](#getBaseJustification--) | आस-पास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। |
| [setBaseJustification(int value)](#setBaseJustification-int-) | आस-पास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। |
| [getMinColumnWidth()](#getMinColumnWidth--) | न्यूनतम स्तम्भ चौड़ाई टविप्स (एक बिंदु का 1/20)। गैप स्पेसिंग (“Column Gap” या “Gap Width”) को MinColumnWidth में जोड़कर कुल Matrix Column Spacing निर्धारित किया जाता है (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी)। |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | न्यूनतम स्तम्भ चौड़ाई टविप्स (एक बिंदु का 1/20)। गैप स्पेसिंग (“Column Gap” या “Gap Width”) को MinColumnWidth में जोड़कर कुल Matrix Column Spacing निर्धारित किया जाता है (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी)। |
| [getColumnGapRule()](#getColumnGapRule--) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या points (टविप्स में संग्रहीत) हो सकती हैं। |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या points (टविप्स में संग्रहीत) हो सकती हैं। |
| [getColumnGap()](#getColumnGap--) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule 3 (“Exactly”) पर सेट है, तो इकाई को टविप्स (एक बिंदु का 1/20) माना जाता है। यदि ColumnGapRule 4 (“Multiple”) पर सेट है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में माना जाता है। |
| [setColumnGap(long value)](#setColumnGap-long-) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule 3 (“Exactly”) पर सेट है, तो इकाई को टविप्स (एक बिंदु का 1/20) माना जाता है। यदि ColumnGapRule 4 (“Multiple”) पर सेट है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में माना जाता है। |
| [getRowGapRule()](#getRowGapRule--) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ lines या points (टविप्स में संग्रहीत) हो सकती हैं। |
| [setRowGapRule(int value)](#setRowGapRule-int-) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ lines या points (टविप्स में संग्रहीत) हो सकती हैं। |
| [getRowGap()](#getRowGap--) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule 3 (“Exactly”) पर सेट है, तो इकाई को टविप्स (एक बिंदु का 1/20) माना जाता है। यदि RowGapRule 4 (“Multiple”) पर सेट है, तो इकाई को आधी-लाइन के रूप में माना जाता है। |
| [setRowGap(long value)](#setRowGap-long-) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule 3 (“Exactly”) पर सेट है, तो इकाई को टविप्स (एक बिंदु का 1/20) माना जाता है। यदि RowGapRule 4 (“Multiple”) पर सेट है, तो इकाई को आधी-लाइन के रूप में माना जाता है। |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | निर्दिष्ट स्तम्भ की क्षैतिज संरेखण प्राप्त करें |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | निर्दिष्ट स्तम्भ की क्षैतिज संरेखण सेट करें |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | निर्दिष्ट स्तम्भों की क्षैतिज संरेखण सेट करें |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | निर्दिष्ट पंक्ति से पहले एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारम्भ में null होते हैं। |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारम्भ में null होते हैं। |
| [deleteRow(int rowIndex)](#deleteRow-int-) | निर्दिष्ट पंक्ति को हटाएँ |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | निर्दिष्ट स्तम्भ से पहले एक नया स्तम्भ डालें। नए स्तम्भ के सभी तत्व प्रारम्भ में null होते हैं। |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | निर्दिष्ट स्तम्भ के बाद एक नया स्तम्भ डालें। नए स्तम्भ के सभी तत्व प्रारम्भ में null होते हैं। |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | निर्दिष्ट स्तम्भ को हटाएँ |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

मैट्रिक्स के तत्व

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | आइटम प्राप्त करने के लिए पंक्ति का शून्य-आधारित सूचकांक |
| column | int | आइटम प्राप्त करने के लिए स्तम्भ का शून्य-आधारित सूचकांक |

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

मैट्रिक्स के तत्व

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | आइटम प्राप्त करने के लिए पंक्ति का शून्य-आधारित सूचकांक |
| column | int | आइटम प्राप्त करने के लिए स्तम्भ का शून्य-आधारित सूचकांक |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

मैट्रिक्स में पंक्तियों की संख्या

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Returns:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

मैट्रिक्स में स्तम्भों की संख्या

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Returns:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Returns:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

आस-पास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। संभावित मान हैं top, bottom, और center। डिफ़ॉल्ट: Center

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```


**Returns:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

आस-पास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। संभावित मान हैं top, bottom, और center। डिफ़ॉल्ट: Center

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

न्यूनतम स्तम्भ चौड़ाई टविप्स (एक बिंदु का 1/20)। गैप स्पेसिंग (“Column Gap” या “Gap Width”) को MinColumnWidth में जोड़कर कुल Matrix Column Spacing निर्धारित किया जाता है (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी)। डिफ़ॉल्ट: 0.

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
```

**Returns:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

न्यूनतम स्तम्भ चौड़ाई टविप्स (एक बिंदु का 1/20)। गैप स्पेसिंग (“Column Gap” या “Gap Width”) को MinColumnWidth में जोड़कर कुल Matrix Column Spacing निर्धारित किया जाता है (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी)। डिफ़ॉल्ट: 0.

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या points (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या points (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule 3 (“Exactly”) पर सेट है, तो इकाई को टविप्स (एक बिंदु का 1/20) माना जाता है। यदि ColumnGapRule 4 (“Multiple”) पर सेट है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में माना जाता है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Returns:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule 3 (“Exactly”) पर सेट है, तो इकाई को टविप्स (एक बिंदु का 1/20) माना जाता है। यदि ColumnGapRule 4 (“Multiple”) पर सेट है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में माना जाता है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ lines या points (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ lines या points (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule 3 (“Exactly”) पर सेट है, तो इकाई को टविप्स (एक बिंदु का 1/20) माना जाता है। यदि RowGapRule 4 (“Multiple”) पर सेट है, तो इकाई को आधी-लाइन के रूप में माना जाता है। डिफ़ॉल्ट: 0

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Returns:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule 3 (“Exactly”) पर सेट है, तो इकाई को टविप्स (एक बिंदु का 1/20) माना जाता है। यदि RowGapRule 4 (“Multiple”) पर सेट है, तो इकाई को आधी-लाइन के रूप में माना जाता है। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

निर्दिष्ट स्तम्भ की क्षैतिज संरेखण प्राप्त करें

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | शून्य-आधारित स्तम्भ सूचकांक |

**Returns:**
int - निर्दिष्ट स्तम्भ की क्षैतिज संरेखण

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

निर्दिष्ट स्तम्भ की क्षैतिज संरेखण सेट करें

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | शून्य-आधारित स्तम्भ सूचकांक |
| val | int | निर्दिष्ट स्तम्भ की नई क्षैतिज संरेखण मान |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

निर्दिष्ट स्तम्भों की क्षैतिज संरेखण सेट करें

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | संरेखण सेट करने के लिए पहले स्तम्भ का शून्य-आधारित सूचकांक |
| columnsCount | long | संरेखण निर्दिष्ट करने के लिए स्तम्भों की संख्या |
| val | int | निर्दिष्ट स्तम्भ की नई क्षैतिज संरेखण मान |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

निर्दिष्ट पंक्ति से पहले एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारम्भ में null होते हैं।

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | नई पंक्ति डालने के लिए मौजूदा पंक्ति का सूचकांक |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारम्भ में null होते हैं।

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | नई पंक्ति डालने के बाद वाली पंक्ति का सूचकांक |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

निर्दिष्ट पंक्ति को हटाएँ

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | हटाने वाली पंक्ति का शून्य-आधारित सूचकांक |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

निर्दिष्ट स्तम्भ से पहले एक नया स्तम्भ डालें। नए स्तम्भ के सभी तत्व प्रारम्भ में null होते हैं।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | नई स्तम्भ डालने के लिए मौजूदा स्तम्भ का सूचकांक |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

निर्दिष्ट स्तम्भ के बाद एक नया स्तम्भ डालें। नए स्तम्भ के सभी तत्व प्रारम्भ में null होते हैं।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | नई स्तम्भ डालने के बाद वाली स्तम्भ का सूचकांक |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

निर्दिष्ट स्तम्भ को हटाएँ

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | हटाने वाले स्तम्भ का शून्य-आधारित सूचकांक |