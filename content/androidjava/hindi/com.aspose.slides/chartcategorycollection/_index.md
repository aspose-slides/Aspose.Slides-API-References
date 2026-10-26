---
title: ChartCategoryCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: संग्रह का प्रतिनिधित्व करता है
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

एक [ChartCategory](../../com.aspose.slides/chartcategory) का प्रतिनिधित्व करता है
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [getUseCells()](#getUseCells--) | यदि सत्य है तो वर्कशीट का उपयोग वर्गों को संग्रहीत करने के लिए किया जाता है (यह मामला बहु-स्तरीय वर्गों का समर्थन करता है)। |
| [setUseCells(boolean value)](#setUseCells-boolean-) | यदि सत्य है तो वर्कशीट का उपयोग वर्गों को संग्रहीत करने के लिए किया जाता है (यह मामला बहु-स्तरीय वर्गों का समर्थन करता है)। |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | उपयोग किए गए वर्ग समूह स्तरों की गिनती लौटाता है। |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | यदि वर्ग संग्रह में मौजूद है, तो उसे लौटाता है। |
| [add(Object value)](#add-java.lang.Object-) | मान से नया [ChartCategory](../../com.aspose.slides/chartcategory) बनाता है और उसे संग्रह में जोड़ता है। |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | निर्दिष्ट [ChartCategory](../../com.aspose.slides/chartcategory) को खोजता है और पूरे संग्रह में पहली उपस्थिति का शून्य-आधारित अनुक्रमांक लौटाता है। |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | उल्लिखित अनुक्रमांक पर तत्व को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह को इटरैट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटरटर लौटाता है। |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह के सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मूल्य लौटाता है जो दर्शाता है कि सूची तक पहुंच समकालिक (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक ऑब्जेक्ट लौटाता है जिसका उपयोग संग्रह तक पहुंच को समकालिक करने के लिए किया जा सकता है। |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```


निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - निर्दिष्ट अनुक्रमांक पर तत्व।

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```


यदि सत्य है तो वर्कशीट वर्गों को संग्रहीत करने के लिए उपयोग की जाती है (यह मामला बहु-स्तरीय वर्गों का समर्थन करता है)। यदि असत्य है तो वर्कशीट मानों को संग्रहीत करने के लिए उपयोग नहीं की जाती (और यह मामला बहु-स्तरीय वर्गों का समर्थन नहीं करता)। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```


यदि सत्य है तो वर्कशीट वर्गों को संग्रहीत करने के लिए उपयोग की जाती है (यह मामला बहु-स्तरीय वर्गों का समर्थन करता है)। यदि असत्य है तो वर्कशीट मानों को संग्रहीत करने के लिए उपयोग नहीं की जाती (और यह मामला बहु-स्तरीय वर्गों का समर्थन नहीं करता)। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```


उपयोग किए गए वर्ग समूह स्तरों की गिनती लौटाता है। बहु-स्तरीय वर्गों के लिए यह एक से अधिक होता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```


यदि वर्ग संग्रह में मौजूद है, तो उसे लौटाता है। अन्यथा [IChartDataCell](../../com.aspose.slides/ichartdatacell) से नया चार्ट वर्ग बनाता है और उसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | चार्ट वर्ग बनाने के लिए उपयोग किया गया सेल। |

**रिटर्न:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - जोड़ा गया या मौजूदा वर्ग।

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```


मान से नया [ChartCategory](../../com.aspose.slides/chartcategory) बनाता है और उसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object | मान।

--------------------

यह मेथड नाम AUTO_DATA वाली वर्कशीट जोड़ता है और सभी मानों को वहां जोड़ता है। यदि आप [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) का उपयोग करके सेल मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस वर्कशीट का उपयोग न करें। इस मेथड का उपयोग करके जोड़े गए मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए |

**रिटर्न:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - जोड़ा गया [IChartCategory](../../com.aspose.slides/ichartcategory)।

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```


निर्दिष्ट [ChartCategory](../../com.aspose.slides/chartcategory) को खोजता है और पूरे संग्रह में पहली उपस्थिति का शून्य-आधारित अनुक्रमांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | चार्ट वर्ग। |

**रिटर्न:**
int - यदि मान पूरे CollectionBase में मिला तो उसके पहले प्रकट होने का शून्य-आधारित अनुक्रमांक; अन्यथा -1।

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```


निर्दिष्ट मान को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | मान।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


उल्लिखित अनुक्रमांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए वर्ग का अनुक्रमांक।

### clear() {#clear--}
```
public final void clear()
```


संग्रह से सभी तत्वों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```


एक एन्यूमरेटर लौटाता है जो संग्रह को इटरैट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - संग्रह को इटरैट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```


पूरे संग्रह के लिए जावा इटरटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - पूरे संग्रह के लिए java.util.Iterator।

### size() {#size--}
```
public final int size()
```


संग्रह में तत्वों की संख्या लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संग्रह के सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | ऐरे में आरंभिक अनुक्रमांक।

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मूल्य लौटाता है जो दर्शाता है कि सूची तक पहुंच समकालिक (थ्रेड-सेफ) है या नहीं। केवल पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक ऑब्जेक्ट लौटाता है जिसका उपयोग संग्रह तक पहुंच को समकालिक करने के लिए किया जा सकता है। केवल पढ़ने योग्य Object.

समकालिकता रूट लौटाता है। केवल पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object