---
title: CachedChartValue
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक कैश्ड चार्ट मान का प्रतिनिधित्व करता है, जैसे X, Y, बबल आकार या मुख्य मान।
type: docs
url: /hi/com.aspose.slides/cachedchartvalue/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

एक कैश्ड चार्ट मान का प्रतिनिधित्व करता है (उदा., X, Y, बबल आकार, या मुख्य मान)।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [toString()](#toString--) | कैश्ड मान का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [toDouble()](#toDouble--) | कैश्ड मान को डबल में बदलता है। |
| [getData()](#getData--) | कैश्ड डेटा ऑब्जेक्ट प्राप्त करता है। |

### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```

### toString() {#toString--}
```
public String toString()
```

कैश्ड मान का स्ट्रिंग प्रतिनिधित्व लौटाता है।

**रिटर्न:**
java.lang.String

### toDouble() {#toDouble--}
```
public final double toDouble()
```

कैश्ड मान को डबल में बदलता है।

**रिटर्न:**
double - संख्यात्मक प्रतिनिधित्व, या Double.NaN यदि Data (\#getData.getData/\#setData(Object).setData(Object)) null है या डबल में परिवर्तित नहीं किया जा सकता।

### getData() {#getData--}
```
public final Object getData()
```

कैश्ड डेटा ऑब्जेक्ट प्राप्त करता है। केवल- पढ़ने योग्य Object .

**रिटर्न:**
java.lang.Object