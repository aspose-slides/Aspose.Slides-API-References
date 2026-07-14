---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: pptx प्रस्तुति दस्तावेज़ में संग्रहित किए जा सकने वाले स्ट्रिंग या डबल मान को दो तरीकों से दर्शाता है: 1) चार्ट से संबंधित वर्कबुक के सेल/सेलों में 2) मौलिक मान के रूप में।
type: docs
url: /hi/com.aspose.slides/stringordoublechartvalue/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

pptx प्रस्तुति दस्तावेज़ में संग्रहित किए जा सकने वाले स्ट्रिंग या डबल मानको दो तरीकों से दर्शाया जाता है: 1) चार्ट से संबंधित वर्कबुक के सेल/सेलों में; 2) मौलिक मान के रूप में।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAsCell()](#getAsCell--) | चार्ट डेटा सेल को प्राप्त करता है या सेट करता है। |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | चार्ट डेटा सेल को प्राप्त करता है या सेट करता है। |
| [getAsLiteralString()](#getAsLiteralString--) | मान को लिटरल स्ट्रिंग के रूप में प्राप्त करता है या सेट करता है। |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | मान को लिटरल स्ट्रिंग के रूप में प्राप्त करता है या सेट करता है। |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | मान को लिटरल डबल के रूप में प्राप्त करता है या सेट करता है। |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | मान को लिटरल डबल के रूप में प्राप्त करता है या सेट करता है। |
| [getData()](#getData--) | Data ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [setData(Object value)](#setData-java.lang.Object-) | Data ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [toDouble()](#toDouble--) | डबल में परिवर्तित करता है। |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

चार्ट डेटा सेल को प्राप्त करता है या सेट करता है। पढ़ने/लेखन [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

चार्ट डेटा सेल को प्राप्त करता है या सेट करता है। पढ़ने/लेखन [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

मान को लिटरल स्ट्रिंग के रूप में प्राप्त करता है या सेट करता है। पढ़ने/लेखन String।

**रिटर्न:**  
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

मान को लिटरल स्ट्रिंग के रूप में प्राप्त करता है या सेट करता है। पढ़ने/लेखन String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

मान को लिटरल डबल के रूप में प्राप्त करता है या सेट करता है। पढ़ने/लेखन double।

**रिटर्न:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

मान को लिटरल डबल के रूप में प्राप्त करता है या सेट करता है। पढ़ने/लेखन double।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Data ऑब्जेक्ट को प्राप्त करता है या सेट करता है। पढ़ने/लेखन Object।

**रिटर्न:**  
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Data ऑब्जेक्ट को प्राप्त करता है या सेट करता है। पढ़ने/लेखन Object।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

डबल में परिवर्तित करता है।

**रिटर्न:**  
double - डबल मान।