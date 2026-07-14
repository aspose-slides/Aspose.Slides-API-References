---
title: IStringChartValue
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: pptx प्रस्तुति दस्तावेज़ में स्ट्रिंग मान को दो तरीकों से संग्रहीत किया जा सकता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेलों में 2) लिटरल मान के रूप में।
type: docs
url: /hi/com.aspose.slides/istringchartvalue/
---
**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

pptx प्रस्तुति दस्तावेज़ में स्ट्रिंग मान को दो तरीकों से संग्रहीत किया जा सकता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेलों में; 2) लिटरल मान के रूप में।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल स्ट्रिंग को लौटाता है या सेट करता है। |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | यदि DataSourceType प्रॉपर्टी DataSourceType.StringLiterals है तो लिटरल स्ट्रिंग को लौटाता है या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | निर्दिष्ट सेल से मान सेट करता है। |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | यदि DataSourceType प्रॉपर्टी DataSourceType.Worksheet है तो यह मेथड वर्कबुक में उन सेल्स का पता लौटाता है जो स्ट्रिंग डेटा का प्रतिनिधित्व करती हैं। |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

स्ट्रिंग प्रतिनिधित्व लौटाता है।

**रिटर्न:**
java.lang.String - String प्रतिनिधित्व एक मान String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

निर्दिष्ट सेल से मान सेट करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | सेल. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

यदि DataSourceType प्रॉपर्टी DataSourceType.Worksheet है तो यह मेथड वर्कबुक में उन सेल्स का पता लौटाता है जो स्ट्रिंग डेटा का प्रतिनिधित्व करती हैं। अन्यथा खाली स्ट्रिंग लौटाता है।

**रिटर्न:**
java.lang.String - String मान String