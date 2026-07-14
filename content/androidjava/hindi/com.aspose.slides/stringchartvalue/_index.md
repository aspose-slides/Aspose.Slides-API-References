---
title: StringChartValue
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: pptx प्रस्तुति दस्तावेज़ में स्ट्रिंग मान को दो तरीकों से संग्रहीत किया जा सकता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेल्स में, 2) लिटेरल मान के रूप में।
type: docs
url: /hi/com.aspose.slides/stringchartvalue/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)  
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

pptx प्रस्तुति दस्तावेज़ में दो तरीकों से स्ट्रिंग मान संग्रहीत किया जा सकता है: 1) चार्ट से संबंधित वर्कबुक की सेल/सेल्स में; 2) लिटेरल मान के रूप में।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAsCells()](#getAsCells--) | नल मान को असाइन करना अनुमति नहीं है। |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | नल मान को असाइन करना अनुमति नहीं है। |
| [getAsLiteralString()](#getAsLiteralString--) | लिटेरल स्ट्रिंग के रूप में मान को रिटर्न या सेट करता है। |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | लिटेरल स्ट्रिंग के रूप में मान को रिटर्न या सेट करता है। |
| [getData()](#getData--) | डेटा ऑब्जेक्ट को रिटर्न या सेट करता है। |
| [setData(Object value)](#setData-java.lang.Object-) | डेटा ऑब्जेक्ट को रिटर्न या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग मान डेटा लौटाता है। |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | निर्दिष्ट सेल से मान सेट करता है। |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | यदि DataSourceType प्रॉपर्टी DataSourceType.Worksheet है तो यह मेथड वर्कबुक में उन सेल्स का एड्रेस लौटाता है जो स्ट्रिंग डेटा का प्रतिनिधित्व करते हैं। |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

नल मान को असाइन करना अनुमति नहीं है। लौटाया गया मान हमेशा नल नहीं होता। पढ़ें/लिखें [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**रिटर्न:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

नल मान को असाइन करना अनुमति नहीं है। लौटाया गया मान हमेशा नल नहीं होता। पढ़ें/लिखें [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

लिटेरल स्ट्रिंग के रूप में मान को रिटर्न या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

लिटेरल स्ट्रिंग के रूप में मान को रिटर्न या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

डेटा ऑब्जेक्ट को रिटर्न या सेट करता है। पढ़ें/लिखें Object.

**रिटर्न:**  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

डेटा ऑब्जेक्ट को रिटर्न या सेट करता है। पढ़ें/लिखें Object.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

स्ट्रिंग मान डेटा लौटाता है। यदि DataSourceType झूठा है और कोई स्ट्रिंग मान असाइन नहीं किया गया है तो नल लौटाएँ।

**रिटर्न:**  
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

निर्दिष्ट सेल से मान सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

यदि DataSourceType प्रॉपर्टी DataSourceType.Worksheet है तो यह मेथड वर्कबुक में उन सेल्स का एड्रेस लौटाता है जो स्ट्रिंग डेटा का प्रतिनिधित्व करते हैं। अन्यथा खाली स्ट्रिंग लौटाएँ।

**रिटर्न:**  
java.lang.String