---
title: ChartCategoryCollection
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: के संग्रह का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/chartcategorycollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

[ChartCategory](../../com.aspose.slides/chartcategory) का संग्रह दर्शाता है
## विधियां

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [getUseCells()](#getUseCells--) | यदि true है तो कार्यपत्रक को श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (इस मामले में बहु-स्तरीय श्रेणियों का समर्थन करता है)। |
| [setUseCells(boolean value)](#setUseCells-boolean-) | यदि true है तो कार्यपत्रक को श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (इस मामले में बहु-स्तरीय श्रेणियों का समर्थन करता है)। |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | उपयोग किए गए श्रेणी समूह स्तरों की गिनती लौटाता है। |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | यदि श्रेणी संग्रह में मौजूद है, तो उसे लौटाएँ। |
| [add(Object value)](#add-java.lang.Object-) | मान से नया [ChartCategory](../../com.aspose.slides/chartcategory) बनाता है और उसे संग्रह में जोड़ता है। |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | निर्दिष्ट [ChartCategory](../../com.aspose.slides/chartcategory) को खोजता है और पूरे संग्रह में पहली घटना का शून्य-आधारित सूचकांक लौटाता है। |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | दिए गए सूचकांक पर तत्व को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [iterator()](#iterator--) | एक इटरेटर लौटाता है जो संग्रह पर पुनरावृत्ति करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को निर्दिष्ट array में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि सूची तक पहुँच समकालिक (थ्रेड सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक वस्तु लौटाता है जिसका उपयोग संग्रह तक पहुँच को समकालिक करने के लिए किया जा सकता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - निर्दिष्ट सूचकांक पर तत्व।

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

यदि true है तो कार्यपत्रक को श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (यह केस बहु-स्तरीय श्रेणियों का समर्थन करता है)। यदि false है तो कार्यपत्रक को मान संग्रहीत करने के लिए उपयोग नहीं किया जाता (और यह केस बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

यदि true है तो कार्यपत्रक को श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (यह केस बहु-स्तरीय श्रेणियों का समर्थन करता है)। यदि false है तो कार्यपत्रक को मान संग्रहीत करने के लिए उपयोग नहीं किया जाता (और यह केस बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

उपयोग किए गए श्रेणी समूह स्तरों की गिनती लौटाता है। मल्टीलेवल श्रेणियों के लिए यह एक से अधिक होता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

यदि श्रेणी संग्रह में मौजूद है, तो उसे लौटाएँ। अन्यथा [IChartDataCell](../../com.aspose.slides/ichartdatacell) से नई चार्ट श्रेणी बनाता है और उसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | चार्ट श्रेणी बनाने के लिए उपयोग किया गया सेल। |

**रिटर्न:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - जोड़ी गई या मौजूदा श्रेणी।

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

मान से नया [ChartCategory](../../com.aspose.slides/chartcategory) बनाता है और उसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object | मान। |

--------------------

यह मेथड नाम AUTO_DATA के साथ कार्यपत्रक जोड़ता है और सभी मान वहाँ जोड़ता है। यदि आप [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) का उपयोग सेल मान जोड़ने या संपादित करने के लिए करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्रक का उपयोग न करें। इस मेथड द्वारा जोड़े जाने वाले मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए। |

**रिटर्न:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - जोड़ा गया [IChartCategory](../../com.aspose.slides/ichartcategory)।

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

निर्दिष्ट [ChartCategory](../../com.aspose.slides/chartcategory) को खोजता है और पूरे संग्रह में पहली घटना का शून्य-आधारित सूचकांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | चार्ट श्रेणी। |

**रिटर्न:**
int - यदि मान पूरे CollectionBase में पाया जाता है तो उसकी पहली घटना का शून्य-आधारित सूचकांक; अन्यथा -1।

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

निर्दिष्ट मान को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | मान। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

दिए गए सूचकांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए श्रेणी का सूचकांक। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी तत्वों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

एक इटरेटर लौटाता है जो संग्रह पर पुनरावृत्ति करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - संग्रह पर पुनरावृत्ति करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

पूरा संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - पूरे संग्रह के लिए एक java.util.Iterator।

### size() {#size--}
```
public final int size()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित array। |
| index | int | array में प्रारम्भिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि सूची तक पहुँच समकालिक (थ्रेड सुरक्षित) है या नहीं। केवल-पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक वस्तु लौटाता है जिसका उपयोग संग्रह तक पहुँच को समकालिक करने के लिए किया जा सकता है। केवल-पढ़ने योग्य Object.

एक समकालिक रूट लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object