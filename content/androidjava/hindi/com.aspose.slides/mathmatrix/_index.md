---
title: MathMatrix
second_title: Aspose.Slides for Android के लिए जावा API संदर्भ
description: एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित बाल तत्वों से बनी मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathmatrix/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

मैट्रिक्स वस्तु को निर्दिष्ट करता है, जिसमें बच्चे तत्व एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित होते हैं। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में अंतर्निहित विभाजक नहीं होते हैं। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलीमीटर वस्तु (IMathDelimiter) का उपयोग करना चाहिए। शून्य तर्कों का उपयोग मैट्रिक्स में अंतर बनाने के लिए किया जा सकता है।

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## निर्माता

| Constructor | Description |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | MathMatrix वर्ग का नया उदाहरण प्रारंभ करता है. |
## विधियाँ

| Method | Description |
| --- | --- |
| [getRowCount()](#getRowCount--) | मैट्रिक्स में पंक्तियों की संख्या |
| [getColumnCount()](#getColumnCount--) | मैट्रिक्स में स्तम्भों की संख्या |
| [getHidePlaceholders()](#getHidePlaceholders--) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छिपाएँ डिफ़ॉल्ट: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छिपाएँ डिफ़ॉल्ट: false |
| [getBaseJustification()](#getBaseJustification--) | आसपास के टेक्स्ट के सापेक्ष ऊर्ध्वाधर समानुपात निर्दिष्ट करता है। |
| [setBaseJustification(int value)](#setBaseJustification-int-) | आसपास के टेक्स्ट के सापेक्ष ऊर्ध्वाधर समानुपात निर्दिष्ट करता है। |
| [getMinColumnWidth()](#getMinColumnWidth--) | ट्विप्स में न्यूनतम स्तम्भ चौड़ाई (1/20वाँ बिंदु) गैप स्पेसिंग (\u201cColumn Gap\u201d या \u201cGap Width\u201d कहलाती है) को MinColumnWidth में जोड़ा जाता है जिससे कुल मैट्रिक्स स्तम्भ स्पेसिंग (विभिन्न स्तम्भों के समान किनारों के बीच दूरी) निर्धारित होती है। |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | ट्विप्स में न्यूनतम स्तम्भ चौड़ाई (1/20वाँ बिंदु) गैप स्पेसिंग (\u201cColumn Gap\u201d या \u201cGap Width\u201d कहलाती है) को MinColumnWidth में जोड़ा जाता है जिससे कुल मैट्रिक्स स्तम्भ स्पेसिंग (विभिन्न स्तम्भों के समान किनारों के बीच दूरी) निर्धारित होती है। |
| [getColumnGapRule()](#getColumnGapRule--) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। |
| [getColumnGap()](#getColumnGap--) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20वाँ बिंदु) के रूप में व्याख्या की जाती है। यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को 0.5 em इंक्रीमेंट्स की संख्या के रूप में व्याख्या की जाती है। |
| [setColumnGap(long value)](#setColumnGap-long-) | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20वाँ बिंदु) के रूप में व्याख्या की जाती है। यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को 0.5 em इंक्रीमेंट्स की संख्या के रूप में व्याख्या की जाती है। |
| [getRowGapRule()](#getRowGapRule--) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइनों या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। |
| [setRowGapRule(int value)](#setRowGapRule-int-) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइनों या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। |
| [getRowGap()](#getRowGap--) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20वाँ बिंदु) के रूप में व्याख्या की जाती है। यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को आधी लाइनों के रूप में व्याख्या की जाती है। |
| [setRowGap(long value)](#setRowGap-long-) | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20वाँ बिंदु) के रूप में व्याख्या की जाती है। यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को आधी लाइनों के रूप में व्याख्या की जाती है। |
| [get_Item(int row, int column)](#get-Item-int-int-) | मैट्रिक्स का तत्व |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | मैट्रिक्स का तत्व |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | कंट्रोल कैरेक्टर प्रॉपर्टीज़ |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | निर्दिष्ट स्तम्भ का क्षैतिज संरेखण प्राप्त करें |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | निर्दिष्ट स्तम्भ का क्षैतिज संरेखण सेट करें |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | निर्दिष्ट स्तम्भों का क्षैतिज संरेखण सेट करें |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | निर्दिष्ट पंक्ति से पहले नई पंक्ति सम्मिलित करें। नई पंक्ति के सभी तत्व प्रारंभ में null होते हैं। |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | निर्दिष्ट पंक्ति के बाद नई पंक्ति सम्मिलित करें। नई पंक्ति के सभी तत्व प्रारंभ में null होते हैं। |
| [deleteRow(int rowIndex)](#deleteRow-int-) | निर्दिष्ट पंक्ति को हटाता है |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | निर्दिष्ट स्तम्भ से पहले नई स्तम्भ सम्मिलित करें। नई स्तम्भ के सभी तत्व प्रारंभ में null होते हैं। |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | निर्दिष्ट स्तम्भ के बाद नई स्तम्भ सम्मिलित करें। नई स्तम्भ के सभी तत्व प्रारंभ में null होते हैं। |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | निर्दिष्ट स्तम्भ को हटाता है |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

MathMatrix वर्ग का नया उदाहरण प्रारंभ करता है.

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

**वापसी:**  
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

**वापसी:**  
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छिपाएँ डिफ़ॉल्ट: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**वापसी:**  
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छिपाएँ डिफ़ॉल्ट: false

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

आसपास के टेक्स्ट के सापेक्ष ऊर्ध्वाधर समानुपात निर्दिष्ट करता है। संभावित मान top, bottom, और center हैं। डिफ़ॉल्ट: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**वापसी:**  
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

आसपास के टेक्स्ट के सापेक्ष ऊर्ध्वाधर समानुपात निर्दिष्ट करता है। संभावित मान top, bottom, और center हैं। डिफ़ॉल्ट: Center

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

ट्विप्स में न्यूनतम स्तम्भ चौड़ाई (1/20वाँ बिंदु) गैप स्पेसिंग (\u201cColumn Gap\u201d या \u201cGap Width\u201d कहलाती है) को MinColumnWidth में जोड़ा जाता है जिससे कुल मैट्रिक्स स्तम्भ स्पेसिंग (विभिन्न स्तम्भों के समान किनारों के बीच दूरी) निर्धारित होती है। डिफ़ॉल्ट: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**वापसी:**  
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

ट्विप्स में न्यूनतम स्तम्भ चौड़ाई (1/20वाँ बिंदु) गैप स्पेसिंग (\u201cColumn Gap\u201d या \u201cGap Width\u201d कहलाती है) को MinColumnWidth में जोड़ा जाता है जिससे कुल मैट्रिक्स स्तम्भ स्पेसिंग (विभिन्न स्तम्भों के समान किनारों के बीच दूरी) निर्धारित होती है। डिफ़ॉल्ट: 0.

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

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**वापसी:**  
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

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

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20वाँ बिंदु) के रूप में व्याख्या की जाती है। यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को 0.5 em इंक्रीमेंट्स की संख्या के रूप में व्याख्या की जाती है। अन्य मामलों में अनदेखा। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**वापसी:**  
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20वाँ बिंदु) के रूप में व्याख्या की जाती है। यदि ColumnGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को 0.5 em इंक्रीमेंट्स की संख्या के रूप में व्याख्या की जाती है। अन्य मामलों में अनदेखा। डिफ़ॉल्ट: 0

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

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइनों या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**वापसी:**  
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइनों या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

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

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20वाँ बिंदु) के रूप में व्याख्या की जाती है। यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को आधी लाइनों के रूप में व्याख्या की जाती है। डिफ़ॉल्ट: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**वापसी:**  
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 (“Exactly”) पर सेट किया गया है, तो इकाई को ट्विप्स (1/20वाँ बिंदु) के रूप में व्याख्या की जाती है। यदि RowGapRule को 4 (“Multiple”) पर सेट किया गया है, तो इकाई को आधी लाइनों के रूप में व्याख्या की जाती है। डिफ़ॉल्ट: 0

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
| row | int | प्राप्त करने के लिए पंक्ति का शून्य-आधारित सूचकांक |
| column | int | प्राप्त करने के लिए स्तम्भ का शून्य-आधारित सूचकांक |

**वापसी:**  
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
| row | int | प्राप्त करने के लिए पंक्ति का शून्य-आधारित सूचकांक |
| column | int | प्राप्त करने के लिए स्तम्भ का शून्य-आधारित सूचकांक |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

कंट्रोल कैरेक्टर प्रॉपर्टीज़

**वापसी:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

निर्दिष्ट स्तम्भ का क्षैतिज संरेखण प्राप्त करें

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
| columnIndex | int | शून्य-आधारित स्तम्भ सूचकांक |

**वापसी:**  
int - निर्दिष्ट स्तम्भ का क्षैतिज संरेखण
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

निर्दिष्ट स्तम्भ का क्षैतिज संरेखण सेट करें

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
| columnIndex | int | शून्य-आधारित स्तम्भ सूचकांक |
| val | int | निर्दिष्ट स्तम्भ के क्षैतिज संरेखण का नया मान |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

निर्दिष्ट स्तम्भों का क्षैतिज संरेखण सेट करें

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
| columnIndex | int | पहला स्तम्भ जिसका संरेखण सेट किया जाना है, का शून्य-आधारित सूचकांक |
| columnsCount | long | उन स्तम्भों की संख्या जिनका संरेखण निर्दिष्ट किया जाना है |
| val | int | निर्दिष्ट स्तम्भ के क्षैतिज संरेखण का नया मान |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

निर्दिष्ट पंक्ति से पहले नई पंक्ति सम्मिलित करें। नई पंक्ति के सभी तत्व प्रारंभ में null होते हैं।

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
| rowIndex | int | नई पंक्ति को सम्मिलित करने से पहले की पंक्ति का सूचकांक |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

निर्दिष्ट पंक्ति के बाद नई पंक्ति सम्मिलित करें। नई पंक्ति के सभी तत्व प्रारंभ में null होते हैं।

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
| rowIndex | int | नई पंक्ति को सम्मिलित करने के बाद की पंक्ति का सूचकांक |

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
| rowIndex | int | हटाने के लिए पंक्ति का शून्य-आधारित सूचकांक। |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

निर्दिष्ट स्तम्भ से पहले नई स्तम्भ सम्मिलित करें। नई स्तम्भ के सभी तत्व प्रारंभ में null होते हैं।

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
| columnIndex | int | नई स्तम्भ को सम्मिलित करने से पहले की स्तम्भ का सूचकांक |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

निर्दिष्ट स्तम्भ के बाद नई स्तम्भ सम्मिलित करें। नई स्तम्भ के सभी तत्व प्रारंभ में null होते हैं।

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
| columnIndex | int | नई स्तम्भ को सम्मिलित करने के बाद की स्तम्भ का सूचकांक |

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
| columnIndex | int | हटाने के लिए स्तम्भ का शून्य-आधारित सूचकांक। |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

संतान तत्व प्राप्त करें

**वापसी:**  
com.aspose.slides.IMathElement[]