---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक कस्टम विभाजन के साथ बार-ऑफ-पाई या पाई-ऑफ-पाई चार्ट में विभाजन बिंदु के लिए बिंदुओं के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/piesplitcustompointcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split.

## विधियां

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक के लिए चार्ट डेटा बिंदु लौटाता है। |
| [add(int dataPointIndex)](#add-int-) | पैरेंट सीरीज़ पॉइंट्स संग्रह में उसके अनुक्रमांक द्वारा डेटा बिंदु जोड़ता है। |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | डेटा बिंदु को संग्रह में जोड़ता है। |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | संग्रह से वस्तु को हटाता है। |
| [remove(int dataPointIndex)](#remove-int-) | पैरेंट सीरीज़ पॉइंट्स संग्रह में उसके अनुक्रमांक द्वारा संग्रह से वस्तु को हटाता है। |
| [clear()](#clear--) | सभी वस्तुओं को [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाता है। |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | निर्धारित करता है कि क्या [IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मान मौजूद है। |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक एरे में कॉपी करता है, विशेष एरे अनुक्रमांक से शुरू करते हुए। |
| [size()](#size--) | चार्ट डेटा बिंदुओं की गिनती लौटाता है या सेट करता है। |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) पढ़ने-के-लिए-केवल है या नहीं दर्शाने वाला मान प्राप्त करता है। |
| [isSynchronized()](#isSynchronized--) | संग्रह तक पहुँच समन्वित (थ्रेड-सेफ़) है या नहीं दर्शाने वाला मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | समन्वयन मूल लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटररेट करने वाला एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटररेटर लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

निर्दिष्ट अनुक्रमांक के लिए चार्ट डेटा बिंदु लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | इंडेक्स। |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - चार्ट डेटा बिंदु।

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

पैरेंट सीरीज़ पॉइंट्स संग्रह में उसके अनुक्रमांक द्वारा डेटा बिंदु जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | int | पैरेंट सीरीज़ पॉइंट्स संग्रह में डेटा बिंदु का अनुक्रमांक। |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

डेटा बिंदु को संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | डेटा बिंदु जिसमें जोड़ा जाना है। |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

संग्रह से वस्तु को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | डेटा बिंदु जिसे हटाया जाना है। |

**रिटर्न:**
boolean - यदि वस्तु सफलतापूर्वक हटाई गई हो तो true; अन्यथा false। यह विधि false भी लौटाती है यदि वस्तु System.Collections.Generic.List\{T\} में नहीं मिली।

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

पैरेंट सीरीज़ पॉइंट्स संग्रह में उसके अनुक्रमांक द्वारा संग्रह से वस्तु को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | int | पैरेंट सीरीज़ पॉइंट्स संग्रह में डेटा बिंदु का अनुक्रमांक। |

### clear() {#clear--}
```
public final void clear()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) से सभी वस्तुओं को हटाता है।

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

निर्धारित करता है कि क्या [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजने के लिये ऑब्जेक्ट। |

**रिटर्न:**
boolean - यदि वस्तु [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाई जाती है तो true; अन्यथा false।

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक एरे में कॉपी करता है, विशेष एरे अनुक्रमांक से शुरू करते हुए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | एक-आयामी एरे जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का गंतव्य है। एरे का शून्य-आधारित अनुक्रमण होना चाहिए। |
| arrayIndex | int | एरे में वह शून्य-आधारित अनुक्रमण जहाँ से कॉपी शुरू होती है। |

### size() {#size--}
```
public final int size()
```

चार्ट डेटा बिंदुओं की गिनती लौटाता है या सेट करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) पढ़ने-के-लिए-केवल है या नहीं दर्शाने वाला मान प्राप्त करता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean - यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) पढ़ने-के-लिए-केवल है तो true; अन्यथा false।

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संग्रह तक पहुँच समन्वित (थ्रेड-सेफ़) है या नहीं दर्शाने वाला मान लौटाता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समन्वयन मूल लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

संग्रह के माध्यम से इटररेट करने वाला एन्यूमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

पूरे संग्रह के लिए जावा इटररेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - सम्पूर्ण संग्रह के लिए java.util.Iterator।