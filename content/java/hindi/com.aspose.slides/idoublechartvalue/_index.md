---
title: IDoubleChartValue
second_title: Aspose.Slides के लिए Java API संदर्भ
description: डबल मान का प्रतिनिधित्व करता है जिसे pptx प्रस्तुति दस्तावेज़ में दो तरीकों से संग्रहीत किया जा सकता है: 1) चार्ट से संबंधित कार्यपुस्तिका की सेल/सेलों में, 2) लिटरल मान के रूप में।
type: docs
url: /hi/com.aspose.slides/idoublechartvalue/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

pptx प्रस्तुति दस्तावेज़ में दो तरीकों से डबल मान को संग्रहीत किया जा सकता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेलों में; 2) लिटरल मान के रूप में।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | यदि DataSourceType = Charts.DataSourceType.DoubleLiterals है तो लिटरल डबल मान को प्राप्त या सेट करता है। |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | यदि DataSourceType = Charts.DataSourceType.DoubleLiterals है तो लिटरल डबल मान को प्राप्त या सेट करता है। |
| [toDouble()](#toDouble--) | डबल में परिवर्तित करता है। |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


यदि DataSourceType = Charts.DataSourceType.DoubleLiterals है तो लिटरल डबल मान को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य डबल।

**रिटर्न:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


यदि DataSourceType = Charts.DataSourceType.DoubleLiterals है तो लिटरल डबल मान को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य डबल।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


डबल में परिवर्तित करता है।

**रिटर्न:**
double - डबल मान।