---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides for Java API संदर्भ
description: कस्टम विभाजन के साथ बार-ऑफ़-पाई या पाई-ऑफ़-पाई चार्ट में विभाजन बिंदु के लिए बिंदुओं का संग्रह दर्शाता है।
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

एक कस्टम विभाजन के साथ बार-ऑफ़-पाई या पाई-ऑफ़-पाई चार्ट में विभाजन बिंदु के लिए बिंदुओं का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक के लिए चार्ट डेटा पॉइंट लौटाता है। |
| [add(int dataPointIndex)](#add-int-) | पैरेंट सीरीज पॉइंट्स संग्रह में उसके अनुक्रमांक द्वारा डेटा पॉइंट जोड़ता है। |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | डेटा पॉइंट को संग्रह में जोड़ता है। |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | संग्रह से वस्तु को हटाता है। |
| [remove(int dataPointIndex)](#remove-int-) | पैरेंट सीरीज पॉइंट्स संग्रह में उसके अनुक्रमांक द्वारा संग्रह से वस्तु को हटाता है। |
| [clear()](#clear--) | सभी वस्तुओं को [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाता है। |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं। |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, जो एक विशिष्ट Array अनुक्रमांक से शुरू होता है। |
| [size()](#size--) | चार्ट डेटा पॉइंट्स की गिनती लौटाता या सेट करता है। |
| [isReadOnly()](#isReadOnly--) | एक मान प्राप्त करता है जो बताता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है या नहीं। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो सूचित करता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | समकालिकता मूल (synchronization root) लौटाता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java iterator लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

निर्दिष्ट अनुक्रमांक के लिए चार्ट डेटा पॉइंट लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | अनुक्रमांक। |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - चार्ट डेटा पॉइंट।

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

पैरेंट सीरीज पॉइंट्स संग्रह में उसके अनुक्रमांक द्वारा डेटा पॉइंट जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | int | पैरेंट सीरीज पॉइंट्स संग्रह में डेटा पॉइंट का अनुक्रमांक। |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

डेटा पॉइंट को संग्रह में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | डेटा पॉइंट जहाँ जोड़ा जाता है। |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

संग्रह से वस्तु को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | डेटा पॉइंट जिससे हटाया जाता है। |

**रिटर्न:**  
boolean - true यदि वस्तु सफलतापूर्वक हटाई गई; अन्यथा, false। यह विधि तब भी false लौटाती है जब वस्तु System.Collections.Generic.List\{T\} में नहीं मिली।

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

पैरेंट सीरीज पॉइंट्स संग्रह में उसके अनुक्रमांक द्वारा संग्रह से वस्तु को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | int | पैरेंट सीरीज पॉइंट्स संग्रह में डेटा पॉइंट का अनुक्रमांक। |

### clear() {#clear--}
```
public final void clear()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) से सभी वस्तुएँ हटाता है।

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | वह ऑब्जेक्ट जिसे [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजा जाना है। |

**रिटर्न:**  
boolean - true यदि वस्तु [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाई गई; अन्यथा, false।

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, जो एक विशिष्ट Array अनुक्रमांक से शुरू होता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | एक-आयामी Array जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का गंतव्य है। Array को शून्य-आधारित अनुक्रमणिका होनी चाहिए। |
| arrayIndex | int | Array में शून्य-आधारित अनुक्रमांक जहाँ से कॉपी शुरू होती है। |

### size() {#size--}
```
public final int size()
```

चार्ट डेटा पॉइंट्स की गिनती लौटाता या सेट करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

एक मान प्राप्त करता है जो बताता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean - true यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है; अन्यथा, false।

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो बताता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ) है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक synchronization root लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

एक enumerator लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - एक IGenericEnumerator जिसे संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

पूरे संग्रह के लिए एक java iterator लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - एक java.util.Iterator पूरे संग्रह के लिए।