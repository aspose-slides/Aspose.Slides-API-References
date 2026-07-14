---
title: IDoubleChartValue
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: pptx प्रस्तुति दस्तावेज़ में डबल मान को दो तरीकों से संग्रहित किया जा सकता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेल्स में; 2) लिटरल मान के रूप में।
type: docs
url: /hi/com.aspose.slides/idoublechartvalue/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

pptx प्रस्तुति दस्तावेज़ में डबल मान को दो तरीकों से संग्रहित किया जा सकता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेल्स में; 2) लिटरल मान के रूप में.
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType = Charts.DataSourceType.DoubleLiterals होने पर लिटरल डबल मान को रिटर्न या सेट करता है। |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType = Charts.DataSourceType.DoubleLiterals होने पर लिटरल डबल मान को रिटर्न या सेट करता है। |
| [toDouble()](#toDouble--) | double में बदलता है। |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

DataSourceType = Charts.DataSourceType.DoubleLiterals होने पर लिटरल डबल मान को रिटर्न या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

DataSourceType = Charts.DataSourceType.DoubleLiterals होने पर लिटरल डबल मान को रिटर्न या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

double में बदलता है।

**रिटर्न:**
double - Double मान।