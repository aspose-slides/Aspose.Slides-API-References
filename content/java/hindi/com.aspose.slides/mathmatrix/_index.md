---
title: MathMatrix
second_title: Java के लिए Aspose.Slides API संदर्भ
description: चाइल्ड तत्वों से बनी मैट्रिक्स वस्तु को निर्दिष्ट करता है, जो एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित होते हैं।
type: docs
url: /hi/com.aspose.slides/mathmatrix/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Matrix वस्तु को निर्दिष्ट करता है, जिसमें एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित चाइल्ड तत्व होते हैं। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में निर्मित सीमांकक नहीं होते हैं। मैट्रिक्स को कोष्ठक में रखने के लिए आपको सीमांकक वस्तु (IMathDelimiter) का उपयोग करना चाहिए। शून्य (null) तर्कों का उपयोग मैट्रिक्स में अंतराल बनाने के लिए किया जा सकता है।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | MathMatrix क्लास का एक नया उदाहरण प्रारम्भ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRowCount()](#getRowCount--) | मैट्रिक्स में पंक्तियों की संख्या |
| [getColumnCount()](#getColumnCount--) | मैट्रिक्स में स्तम्भों की संख्या |
| [getHidePlaceholders()](#getHidePlaceholders--) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ डिफ़ॉल्ट: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ डिफ़ॉल्ट: false |
| [getBaseJustification()](#getBaseJustification--) | आसपास के पाठ के सापेक्ष ऊर्ध्वाधर समरेखण निर्दिष्ट करता है। |
| [setBaseJustification(int value)](#setBaseJustification-int-) | आसपास के पाठ के सापेक्ष ऊर्ध्वाधर समरेखण निर्दिष्ट करता है। |
| [getMinColumnWidth()](#getMinColumnWidth--) | न्यूनतम स्तम्भ चौड़ाई ट्विप्स (पॉइंट का 1/20)। गैप स्पेसिंग (जिसे "Column Gap" या "Gap Width" कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल Matrix Column Spacing (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी) निर्धारित की जा सके। |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | न्यूनतम स्तम्भ चौड़ाई ट्विप्स (पॉइंट का 1/20)। गैप स्पेसिंग (जिसे "Column Gap" या "Gap Width" कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल Matrix Column Spacing (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी) निर्धारित की जा सके। |
| [getColumnGapRule()](#getColumnGapRule--) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स हो सकती हैं (ट्वीप्स में संग्रहीत)। |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स हो सकती हैं (ट्वीप्स में संग्रहीत)। |
| [getColumnGap()](#getColumnGap--) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई ट्विप्स (पॉइंट का 1/20) मानी जाती है। यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई 0.5 em वृद्धि की संख्या के रूप में मानी जाती है। |
| [setColumnGap(long value)](#setColumnGap-long-) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई ट्विप्स (पॉइंट का 1/20) मानी जाती है। यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई 0.5 em वृद्धि की संख्या के रूप में मानी जाती है। |
| [getRowGapRule()](#getRowGapRule--) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स हो सकती हैं (ट्वीप्स में संग्रहीत)। |
| [setRowGapRule(int value)](#setRowGapRule-int-) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स हो सकती हैं (ट्वीप्स में संग्रहीत)। |
| [getRowGap()](#getRowGap--) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई ट्विप्स (पॉइंट का 1/20) मानी जाती है। यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई आधी लाइन्स के रूप में मानी जाती है। |
| [setRowGap(long value)](#setRowGap-long-) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई ट्विप्स (पॉइंट का 1/20) मानी जाती है। यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई आधी लाइन्स के रूप में मानी जाती है। |
| [get_Item(int row, int column)](#get-Item-int-int-) | मैट्रिक्स का तत्व |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | मैट्रिक्स का तत्व |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | निर्दिष्ट स्तम्भ की क्षैतिज संरेखण प्राप्त करें |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | निर्दिष्ट स्तम्भ की क्षैतिज संरेखण सेट करें |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | निर्दिष्ट स्तम्भों की क्षैतिज संरेखण सेट करें |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | निर्दिष्ट पंक्ति से पहले एक नई पंक्ति सम्मिलित करें। नई पंक्ति में सभी तत्व प्रारम्भ में null होते हैं। |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | निर्दिष्ट पंक्ति के बाद एक नई पंक्ति सम्मिलित करें। नई पंक्ति में सभी तत्व प्रारम्भ में null होते हैं। |
| [deleteRow(int rowIndex)](#deleteRow-int-) | निर्दिष्ट पंक्ति को हटाता है |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | निर्दिष्ट स्तम्भ से पहले एक नया स्तम्भ सम्मिलित करें। नए स्तम्भ में सभी तत्व प्रारम्भ में null होते हैं। |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | निर्दिष्ट स्तम्भ के बाद एक नया स्तम्भ सम्मिलित करें। नए स्तम्भ में सभी तत्व प्रारम्भ में null होते हैं। |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | निर्दिष्ट स्तम्भ को हटाता है |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

MathMatrix क्लास का एक नया उदाहरण प्रारम्भ करता है।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowCount | int | पंक्तियों की संख्या |
| columnCount | int | स्तम्भों की संख्या |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
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
public final int getColumnCount()
```

मैट्रिक्स में स्तम्भों की संख्या

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
public final boolean getHidePlaceholders()
```

खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ डिफ़ॉल्ट: false

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
public final void setHidePlaceholders(boolean value)
```

खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छुपाएँ डिफ़ॉल्ट: false

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
public final int getBaseJustification()
```

आसपास के पाठ के सापेक्ष ऊर्ध्वाधर समरेखण निर्दिष्ट करता है। संभावित मान top, bottom, और center हैं। डिफ़ॉल्ट: Center

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
public final void setBaseJustification(int value)
```

आसपास के पाठ के सापेक्ष ऊर्ध्वाधर समरेखण निर्दिष्ट करता है। संभावित मान top, bottom, और center हैं। डिफ़ॉल्ट: Center

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
public final long getMinColumnWidth()
```

न्यूनतम स्तम्भ चौड़ाई ट्विप्स (पॉइंट का 1/20)। गैप स्पेसिंग (जिसे "Column Gap" या "Gap Width" कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल Matrix Column Spacing (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी) निर्धारित की जा सके। डिफ़ॉल्ट: 0.

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
public final void setMinColumnWidth(long value)
```

न्यूनतम स्तम्भ चौड़ाई ट्विप्स (पॉइंट का 1/20)। गैप स्पेसिंग (जिसे "Column Gap" या "Gap Width" कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल Matrix Column Spacing (विभिन्न स्तम्भों के समान किनारों के बीच की दूरी) निर्धारित की जा सके। डिफ़ॉल्ट: 0.

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
public final int getColumnGapRule()
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स हो सकती हैं (ट्वीप्स में संग्रहीत)। डिफ़ॉल्ट: SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स हो सकती हैं (ट्वीप्स में संग्रहीत)। डिफ़ॉल्ट: SingleSpacingGap (0)

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
public final long getColumnGap()
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई ट्विप्स (पॉइंट का 1/20) के रूप में समझी जाती है। यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई 0.5 em वृद्धि की संख्या के रूप में समझी जाती है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0

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
public final void setColumnGap(long value)
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई ट्विप्स (पॉइंट का 1/20) के रूप में समझी जाती है। यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई 0.5 em वृद्धि की संख्या के रूप में समझी जाती है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0

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
public final int getRowGapRule()
```

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स हो सकती हैं (ट्वीप्स में संग्रहीत)। डिफ़ॉल्ट: SingleSpacingGap (0)

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
public final void setRowGapRule(int value)
```

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स हो सकती हैं (ट्वीप्स में संग्रहीत)। डिफ़ॉल्ट: SingleSpacingGap (0)

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
public final long getRowGap()
```

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई ट्विप्स (पॉइंट का 1/20) के रूप में समझी जाती है। यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई आधी लाइन्स के रूप में समझी जाती है। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**रिटर्न:**  
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई ट्विप्स (पॉइंट का 1/20) के रूप में समझी जाती है। यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई आधी लाइन्स के रूप में समझी जाती है। डिफ़ॉल्ट: 0

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

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

मैट्रिक्स का तत्व

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
| row | int | आइटम प्राप्त करने के लिए पंक्ति का शून्य-आधारित अनुक्रमणिका |
| column | int | आयटम प्राप्त करने के लिए स्तम्भ का शून्य-आधारित अनुक्रमणिका |

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

मैट्रिक्स का तत्व

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
| row | int | आइटम प्राप्त करने के लिए पंक्ति का शून्य-आधारित अनुक्रमणिका |
| column | int | आइटम प्राप्त करने के लिए स्तम्भ का शून्य-आधारित अनुक्रमणिका |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**रिटर्न:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

निर्दिष्ट स्तम्भ की क्षैतिज संरेखण प्राप्त करें

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
| columnIndex | int | शून्य-आधारित स्तम्भ अनुक्रमणिका |

**रिटर्न:**  
int - निर्दिष्ट स्तम्भ का क्षैतिज संरेखण
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

निर्दिष्ट स्तम्भ की क्षैतिज संरेखण सेट करें

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int | शून्य-आधारित स्तम्भ अनुक्रमणिका |
| val | int | निर्दिष्ट स्तम्भ की क्षैतिज संरेखण का नया मान |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

निर्दिष्ट स्तम्भों की क्षैतिज संरेखण सेट करें

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | int | समरेखण सेट करने के लिए पहले स्तम्भ का शून्य-आधारित अनुक्रमणिका |
| columnsCount | long | समरेखण निर्दिष्ट करने के लिए स्तम्भों की संख्या |
| val | int | निर्दिष्ट स्तम्भ की क्षैतिज संरेखण का नया मान |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

निर्दिष्ट पंक्ति से पहले एक नई पंक्ति सम्मिलित करें। नई पंक्ति में सभी तत्व प्रारम्भ में null होते हैं।

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
| rowIndex | int | नई पंक्ति सम्मिलित करने से पहले पंक्ति का अनुक्रमणिका |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

निर्दिष्ट पंक्ति के बाद एक नई पंक्ति सम्मिलित करें। नई पंक्ति में सभी तत्व प्रारम्भ में null होते हैं।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | int | पंक्ति के बाद नई पंक्ति सम्मिलित करने के लिए अनुक्रमणिका |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

निर्दिष्ट पंक्ति को हटाता है

--------------------

> ```
> उदाहरण:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | int | हटाने के लिए पंक्ति का शून्य-आधारित अनुक्रमणिका। |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

निर्दिष्ट स्तम्भ से पहले एक नया स्तम्भ सम्मिलित करें। नए स्तम्भ में सभी तत्व प्रारम्भ में null होते हैं।

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
| columnIndex | int | नई स्तम्भ सम्मिलित करने से पहले स्तम्भ का अनुक्रमणिका |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

निर्दिष्ट स्तम्भ के बाद एक नया स्तम्भ सम्मिलित करें। नए स्तम्भ में सभी तत्व प्रारम्भ में null होते हैं।

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
| columnIndex | int | स्तम्भ के बाद नई स्तम्भ सम्मिलित करने के लिए अनुक्रमणिका |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

निर्दिष्ट स्तम्भ को हटाता है

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
| columnIndex | int | हटाने के लिए स्तम्भ का शून्य-आधारित अनुक्रमणिका। |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

संतान तत्व प्राप्त करें

**रिटर्न:**  
com.aspose.slides.IMathElement[]