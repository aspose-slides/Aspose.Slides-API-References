---
title: IStringChartValue
second_title: Aspose.Slides के लिए Java API संदर्भ
description: "एक स्ट्रिंग वैल्यू को प्रतिनिधित्व करता है जिसे pptx प्रेजेंटेशन दस्तावेज़ में दो तरीकों से संग्रहीत किया जा सकता है: 1) चार्ट से जुड़े वर्कबुक की सेल/सेलों में, 2) लिटरल वैल्यू के रूप में।"
type: docs
url: /hi/com.aspose.slides/istringchartvalue/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

pptx प्रेजेंटेशन दस्तावेज़ में स्ट्रिंग वैल्यू को दो तरीकों से संग्रहीत किया जा सकता है: 1) चार्ट से जुड़े वर्कबुक की सेल/सेलों में; 2) लिटरल वैल्यू के रूप में।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल स्ट्रिंग को लौटाता है या सेट करता है। |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल स्ट्रिंग को लौटाता है या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | निर्दिष्ट सेल से वैल्यू सेट करता है। |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | यदि DataSourceType प्रॉपर्टी DataSourceType.Worksheet है तो यह मेथड वर्कबुक में उन सेल्स का एड्रेस लौटाता है जो स्ट्रिंग डेटा का प्रतिनिधित्व करते हैं। |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल स्ट्रिंग को लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल स्ट्रिंग को लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

स्ट्रिंग प्रतिनिधित्व लौटाता है।

**रिटर्न:**
java.lang.String - एक वैल्यू String का स्ट्रिंग प्रतिनिधित्व

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

निर्दिष्ट सेल से वैल्यू सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

यदि DataSourceType प्रॉपर्टी DataSourceType.Worksheet है तो यह मेथड वर्कबुक में उन सेल्स का एड्रेस लौटाता है जो स्ट्रिंग डेटा का प्रतिनिधित्व करते हैं। अन्यथा खाली स्ट्रिंग लौटाता है।

**रिटर्न:**
java.lang.String - String value String