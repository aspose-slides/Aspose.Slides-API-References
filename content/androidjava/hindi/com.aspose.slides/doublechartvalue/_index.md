---
title: DoubleChartValue
second_title: Aspose.Slides for Android, Java API रेफ़रेंस के माध्यम से
description: pptx प्रस्तुति दस्तावेज़ में दो तरीकों से संग्रहीत किए जा सकने वाले double मान का प्रतिनिधित्व करता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेलों में 2) लिटरल मान के रूप में।
type: docs
url: /hi/com.aspose.slides/doublechartvalue/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

pptx प्रस्तुति दस्तावेज़ में दो तरीकों से संग्रहीत किए जा सकने वाले double मान का प्रतिनिधित्व करता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेलों में; 2) लिटरल मान के रूप में।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAsCell()](#getAsCell--) | चार्ट डेटा सेल को लौटाता है या सेट करता है। |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | चार्ट डेटा सेल को लौटाता है या सेट करता है। |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | मान को लिटरल double के रूप में लौटाता है या सेट करता है। |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | मान को लिटरल double के रूप में लौटाता है या सेट करता है। |
| [getData()](#getData--) | Data ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setData(Object value)](#setData-java.lang.Object-) | Data ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [toDouble()](#toDouble--) | double में बदलता है। |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

चार्ट डेटा सेल को लौटाता है या सेट करता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

चार्ट डेटा सेल को लौटाता है या सेट करता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

मान को लिटरल double के रूप में लौटाता है या सेट करता है। पढ़ें/लिखें double.

**रिटर्न:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

मान को लिटरल double के रूप में लौटाता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Data ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ें/लिखें Object.

**रिटर्न:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Data ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ें/लिखें Object.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

double में बदलता है।

**रिटर्न:**
double - यदि DataSourceType बराबर DoubleLiterals है तो LiteralDouble लौटाता है। यदि DataSourceType बराबर Worksheet है तो सफलतापूर्वक double सेल मान में परिवर्तित होकर लौटाता है, अन्यथा NaN लौटाता है।