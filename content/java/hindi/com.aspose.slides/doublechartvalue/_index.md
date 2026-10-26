---
title: DoubleChartValue
second_title: "Aspose.Slides for Java API संदर्भ"
description: "pptx प्रस्तुति दस्तावेज़ में दो तरीकों से संग्रहीत किए जा सकने वाले डबल मान को दर्शाता है: 1) चार्ट से संबंधित कार्यपुस्तिका के सेल/सेल्स में 2) शाब्दिक मान के रूप में।"
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

pptx प्रस्तुति दस्तावेज़ में दो तरीकों से डबल मान को प्रदर्शित करता है: 1) चार्ट से संबंधित कार्यपुस्तिका के सेल/सेल्स में; 2) शाब्दिक मान के रूप में।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAsCell()](#getAsCell--) | चार्ट डेटा सेल को लौटाता या सेट करता है। |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | चार्ट डेटा सेल को लौटाता या सेट करता है। |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | मूल्य को शाब्दिक डबल के रूप में लौटाता या सेट करता है। |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | मूल्य को शाब्दिक डबल के रूप में लौटाता या सेट करता है। |
| [getData()](#getData--) | डेटा ऑब्जेक्ट को लौटाता या सेट करता है। |
| [setData(Object value)](#setData-java.lang.Object-) | डेटा ऑब्जेक्ट को लौटाता या सेट करता है। |
| [toDouble()](#toDouble--) | डबल में परिवर्तित करता है। |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

चार्ट डेटा सेल को लौटाता या सेट करता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

चार्ट डेटा सेल को लौटाता या सेट करता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

मूल्य को शाब्दिक डबल के रूप में लौटाता या सेट करता है। पढ़ें/लिखें double.

**रिटर्न:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

मूल्य को शाब्दिक डबल के रूप में लौटाता या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

डेटा ऑब्जेक्ट को लौटाता या सेट करता है। पढ़ें/लिखें Object.

**रिटर्न:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

डेटा ऑब्जेक्ट को लौटाता या सेट करता है। पढ़ें/लिखें Object.

**पैरामीटर्स:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

डबल में परिवर्तित करता है।

**रिटर्न:**
double - यदि DataSourceType बराबर DoubleLiterals है तो LiteralDouble लौटाता है। यदि DataSourceType बराबर Worksheet है तो डबल सेल मान को सफलतापूर्वक रूपांतरित करके लौटाता है, अन्यथा NaN लौटाता है।