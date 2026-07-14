---
title: IChartCategoryCollection
second_title: Aspose.Slides for Android हेतु Java API संदर्भ
description: का संग्रह दर्शाता है
type: docs
url: /hi/com.aspose.slides/ichartcategorycollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

एक [IChartCategory](../../com.aspose.slides/ichartcategory) का संग्रह दर्शाता है
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [getUseCells()](#getUseCells--) | यदि true है तो कार्यपत्रक श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)। |
| [setUseCells(boolean value)](#setUseCells-boolean-) | यदि true है तो कार्यपत्रक श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)। |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | उपयोग की गई श्रेणी समूह स्तरों की गिनती लौटाता है। |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | यदि श्रेणी संग्रह में मौजूद है, तो इसे लौटाएं। |
| [add(Object value)](#add-java.lang.Object-) | value से नया [IChartCategory](../../com.aspose.slides/ichartcategory) बनाता है और इसे संग्रह में जोड़ता है। |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | निर्दिष्ट [IChartCategory](../../com.aspose.slides/ichartcategory) को खोजता है और पूरी Collection में पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है। |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | दिए गए अनुक्रमांक पर तत्व को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
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
public abstract boolean getUseCells()
```

यदि true है तो कार्यपत्रक श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)। यदि false है तो कार्यपत्रक मानों को संग्रहीत करने के लिए उपयोग नहीं किया जाता (और यह मामला बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

यदि true है तो कार्यपत्रक श्रेणियों को संग्रहीत करने के लिए उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)। यदि false है तो कार्यपत्रक मानों को संग्रहीत करने के लिए उपयोग नहीं किया जाता (और यह मामला बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

उपयोग किए गए श्रेणी समूह स्तरों की गिनती लौटाता है। बहु-स्तरीय श्रेणियों के लिये यह एक से अधिक होता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

यदि श्रेणी संग्रह में मौजूद है, तो इसे लौटाएं। अन्यथा [IChartDataCell](../../com.aspose.slides/ichartdatacell) से नई चार्ट श्रेणी बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | चार्ट श्रेणी बनाने के लिए प्रयुक्त सेल। |

**रिटर्न:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - जोड़ी गई या मौजूदा श्रेणी।

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

value से नया [IChartCategory](../../com.aspose.slides/ichartcategory) बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object | मान।

--------------------

यह विधि AUTO\_DATA नामक कार्यपत्रक जोड़ती है और सभी मान वहाँ जोड़ती है। यदि आप [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) का उपयोग करके सेल मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्रक का उपयोग न करें। इस विधि का उपयोग करके जोड़े जाने वाले मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए |

**रिटर्न:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - जोड़ा गया [IChartCategory](../../com.aspose.slides/ichartcategory)।

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

निर्दिष्ट [IChartCategory](../../com.aspose.slides/ichartcategory) को खोजता है और पूरी Collection में पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | चार्ट श्रेणी। |

**रिटर्न:**
int - पूरी CollectionBase में मान की पहली उपस्थिति का शून्य-आधारित सूचकांक, यदि मिला; अन्यथा -1।

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

निर्दिष्ट मान को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | मान।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

दिए गए अनुक्रमांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाई जाने वाली श्रेणी का अनुक्रमांक।

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्वों को हटाता है।