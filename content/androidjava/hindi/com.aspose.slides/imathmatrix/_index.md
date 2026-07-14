---
title: IMathMatrix
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड एलिमेंट्स वाले मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/imathmatrix/
---
**सभी लागू इंटरफेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड एलिमेंट्स होते हैं। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में निर्मित डिलीमीटर नहीं होते। मैट्रिक्स को ब्रैकेट में रखने के लिए आपको डिलीमीटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए। शून्य (null) तर्कों का उपयोग करके मैट्रिक्स में गैप बना सकते हैं।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | मैट्रिक्स के तत्व |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | मैट्रिक्स के तत्व |
| [getRowCount()](#getRowCount--) | मैट्रिक्स में पंक्तियों की संख्या |
| [getColumnCount()](#getColumnCount--) | मैट्रिक्स में स्तंभों की संख्या |
| [getHidePlaceholders()](#getHidePlaceholders--) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर्स छुपाएँ डिफ़ॉल्ट: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर्स छुपाएँ डिफ़ॉल्ट: false |
| [getBaseJustification()](#getBaseJustification--) | आसपास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। |
| [setBaseJustification(int value)](#setBaseJustification-int-) | आसपास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। |
| [getMinColumnWidth()](#getMinColumnWidth--) | twips में न्यूनतम स्तंभ चौड़ाई (1/20 बिंदु)। गैप स्पेसिंग (जिसे \u201cColumn Gap\u201d या \u201cGap Width\u201d कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स स्तंभ अंतर (विभिन्न स्तंभों के समान किनारों के बीच की दूरी) निर्धारित हो सके। |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | twips में न्यूनतम स्तंभ चौड़ाई (1/20 बिंदु)। गैप स्पेसिंग (जिसे \u201cColumn Gap\u201d या \u201cGap Width\u201d कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स स्तंभ अंतर (विभिन्न स्तंभों के समान किनारों के बीच की दूरी) निर्धारित हो सके। |
| [getColumnGapRule()](#getColumnGapRule--) | मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स (twips में संग्रहित) हो सकती हैं। |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स (twips में संग्रहित) हो सकती हैं। |
| [getColumnGap()](#getColumnGap--) | मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule 3 (“Exactly”) पर सेट है, तो इकाई को twips (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule 4 (“Multiple”) पर सेट है, तो इकाई को 0.5 em इंक्रीमेंट की संख्या के रूप में व्याख्यायित किया जाता है। |
| [setColumnGap(long value)](#setColumnGap-long-) | मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule 3 (“Exactly”) पर सेट है, तो इकाई को twips (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule 4 (“Multiple”) पर सेट है, तो इकाई को 0.5 em इंक्रीमेंट की संख्या के रूप में व्याख्यायित किया जाता है। |
| [getRowGapRule()](#getRowGapRule--) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स (twips में संग्रहित) हो सकती हैं। |
| [setRowGapRule(int value)](#setRowGapRule-int-) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स (twips में संग्रहित) हो सकती हैं। |
| [getRowGap()](#getRowGap--) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule 3 (“Exactly”) पर सेट है, तो इकाई को twips (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule 4 (“Multiple”) पर सेट है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। |
| [setRowGap(long value)](#setRowGap-long-) | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule 3 (“Exactly”) पर सेट है, तो इकाई को twips (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule 4 (“Multiple”) पर सेट है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | निर्दिष्ट कॉलम की क्षैतिज संरेखण प्राप्त करें |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | निर्दिष्ट कॉलम की क्षैतिज संरेखण सेट करें |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | निर्दिष्ट कॉलमों की क्षैतिज संरेखण सेट करें |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | निर्दिष्ट पंक्ति के पहले एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारंभ में null होते हैं। |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारंभ में null होते हैं। |
| [deleteRow(int rowIndex)](#deleteRow-int-) | निर्दिष्ट पंक्ति को हटाता है |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | निर्दिष्ट कॉलम के पहले एक नई कॉलम डालें। नई कॉलम के सभी तत्व प्रारंभ में null होते हैं। |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | निर्दिष्ट कॉलम के बाद एक नई कॉलम डालें। नई कॉलम के सभी तत्व प्रारंभ में null होते हैं। |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | निर्दिष्ट कॉलम को हटाता है |

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| row | int | आइटम प्राप्त करने के लिए पंक्ति का शून्य-आधारित इंडेक्स |
| column | int | आइटम प्राप्त करने के लिए कॉलम का शून्य-आधारित इंडेक्स |

**रिटर्न:**
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| row | int | आइटम प्राप्त करने के लिए पंक्ति का शून्य-आधारित इंडेक्स |
| column | int | आइटम प्राप्त करने के लिए कॉलम का शून्य-आधारित इंडेक्स |
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

**रिटर्न:**
int
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

मैट्रिक्स में स्तंभों की संख्या

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**रिटर्न:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर्स छुपाएँ डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**रिटर्न:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर्स छुपाएँ डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

आसपास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। संभावित मान हैं top, bottom, और center। डिफ़ॉल्ट: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**रिटर्न:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

आसपास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। संभावित मान हैं top, bottom, और center। डिफ़ॉल्ट: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

twips में न्यूनतम स्तंभ चौड़ाई (1/20 बिंदु)। गैप स्पेसिंग (जिसे \u201cColumn Gap\u201d या \u201cGap Width\u201d कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स स्तंभ अंतर (विभिन्न स्तंभों के समान किनारों के बीच की दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**रिटर्न:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

twips में न्यूनतम स्तंभ चौड़ाई (1/20 बिंदु)। गैप स्पेसिंग (जिसे \u201cColumn Gap\u201d या \u201cGap Width\u201d कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स स्तंभ अंतर (विभिन्न स्तंभों के समान किनारों के बीच की दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स (twips में संग्रहित) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**रिटर्न:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स (twips में संग्रहित) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule 3 (“Exactly”) पर सेट है, तो इकाई को twips (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule 4 (“Multiple”) पर सेट है, तो इकाई को 0.5 em इंक्रीमेंट की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**रिटर्न:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule 3 (“Exactly”) पर सेट है, तो इकाई को twips (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule 4 (“Multiple”) पर सेट है, तो इकाई को 0.5 em इंक्रीमेंट की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स (twips में संग्रहित) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**रिटर्न:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स (twips में संग्रहित) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule 3 (“Exactly”) पर सेट है, तो इकाई को twips (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule 4 (“Multiple”) पर सेट है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**रिटर्न:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule 3 (“Exactly”) पर सेट है, तो इकाई को twips (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule 4 (“Multiple”) पर सेट है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

निर्दिष्ट कॉलम की क्षैतिज संरेखण प्राप्त करें

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int | शून्य-आधारित कॉलम इंडेक्स |

**रिटर्न:**
int - निर्दिष्ट कॉलम की क्षैतिज संरेखण
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

निर्दिष्ट कॉलम की क्षैतिज संरेखण सेट करें

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int | शून्य-आधारित कॉलम इंडेक्स |
| val | int | निर्दिष्ट कॉलम की नई क्षैतिज संरेखण मान |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

निर्दिष्ट कॉलमों की क्षैतिज संरेखण सेट करें

--------------------

> ```
> उदाहरण:
```



**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int | पहली कॉलम का शून्य-आधारित इंडेक्स जिसके लिए संरेखण सेट किया जाना है |
| columnsCount | long | संरेखण निर्दिष्ट करने के लिए कॉलमों की संख्या |
| val | int | निर्दिष्ट कॉलम की नई क्षैतिज संरेखण मान |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

निर्दिष्ट पंक्ति के पहले एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारंभ में null होते हैं।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | int | उस पंक्ति का इंडेक्स जिसके पहले नई पंक्ति डाली जानी है |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारंभ में null होते हैं।

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | int | उस पंक्ति का इंडेक्स जिसके बाद नई पंक्ति डाली जानी है |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

निर्दिष्ट पंक्ति को हटाता है

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | int | हटाने के लिए पंक्ति का शून्य-आधारित इंडेक्स |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

निर्दिष्ट कॉलम के पहले एक नई कॉलम डालें। नई कॉलम के सभी तत्व प्रारंभ में null होते हैं।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int | उस कॉलम का इंडेक्स जिसके पहले नई कॉलम डालनी है |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

निर्दिष्ट कॉलम के बाद एक नई कॉलम डालें। नई कॉलम के सभी तत्व प्रारंभ में null होते हैं।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int | उस कॉलम का इंडेक्स जिसके बाद नई कॉलम डालनी है |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

निर्दिष्ट कॉलम को हटाता है

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int | हटाने के लिए कॉलम का शून्य-आधारित इंडेक्स |
