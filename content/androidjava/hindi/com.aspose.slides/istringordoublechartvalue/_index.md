---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Android के द्वारा Java API संदर्भ
description: pptx प्रस्तुति दस्तावेज़ में संग्रहीत किए जा सकने वाले string या double मान को दो तरीकों से प्रदर्शित करता है: 1) चार्ट से संबंधित workbook की cell/cells में; 2) लिटरल मान के रूप में।
type: docs
url: /hi/com.aspose.slides/istringordoublechartvalue/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

pptx प्रस्तुति दस्तावेज़ में संग्रहीत किए जा सकने वाले string या double मान को दो तरीकों से प्रदर्शित करता है: 1) चार्ट से संबंधित workbook की cell/cells में; 2) लिटरल मान के रूप में।
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल string को प्राप्त करता है या सेट करता है। |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल string को प्राप्त करता है या सेट करता है। |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | यदि DataSourceType प्रॉपर्टी DataSourceType.DoubleLiterals है तो लिटरल double को प्राप्त करता है या सेट करता है। |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | यदि DataSourceType प्रॉपर्टी DataSourceType.DoubleLiterals है तो लिटरल double को प्राप्त करता है या सेट करता है। |
| [toDouble()](#toDouble--) | मान को double में परिवर्तित करता है। |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल string को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल string को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


यदि DataSourceType प्रॉपर्टी DataSourceType.DoubleLiterals है तो लिटरल double को प्राप्त करता है या सेट करता है। पढ़ें/लिखें double.

**रिटर्न:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


यदि DataSourceType प्रॉपर्टी DataSourceType.DoubleLiterals है तो लिटरल double को प्राप्त करता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


मान को double में परिवर्तित करता है।

**रिटर्न:**  
double - Double value double