---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: एक कैश किया गया चार्ट मान दर्शाता है, जैसे X Y बबल आकार या मुख्य मान.
type: docs
url: /hi/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

एक कैश किया गया चार्ट मान दर्शाता है (जैसे X, Y, बबल आकार, या मुख्य मान)।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getData()](#getData--) | कैश किए गए डेटा ऑब्जेक्ट को प्राप्त करता है। |
| [toDouble()](#toDouble--) | कैश किए गए मान को डबल में परिवर्तित करता है। |
### getData() {#getData--}
```
public abstract Object getData()
```

कैश किए गए डेटा ऑब्जेक्ट को प्राप्त करता है। केवल-पढ़ने योग्य  Object .

**वापसी:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

कैश किए गए मान को डबल में परिवर्तित करता है।

**वापसी:**
double - संख्यात्मक प्रतिनिधित्व, या Double.NaN यदि Data (\#getData.getData) null है या डबल में परिवर्तित नहीं किया जा सकता।