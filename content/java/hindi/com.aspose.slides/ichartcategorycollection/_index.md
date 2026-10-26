---
title: IChartCategoryCollection
second_title: जावा के लिए Aspose.Slides API संदर्भ
description: के संग्रह का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/ichartcategorycollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

यह [IChartCategory](../../com.aspose.slides/ichartcategory) का संग्रह दर्शाता है
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [getUseCells()](#getUseCells--) | यदि true हो तो कार्यपत्रक श्रेणियों को संग्रहीत करने के लिये उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)। |
| [setUseCells(boolean value)](#setUseCells-boolean-) | यदि true हो तो कार्यपत्रक श्रेणियों को संग्रहीत करने के लिये उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)। |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | उपयोग किए गए श्रेणी समूह स्तरों की गणना लौटाता है। |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | यदि श्रेणी संग्रह में मौजूद है, तो इसे लौटाता है। |
| [add(Object value)](#add-java.lang.Object-) | मान से नया [IChartCategory](../../com.aspose.slides/ichartcategory) बनाता है और इसे संग्रह में जोड़ता है। |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | निर्दिष्ट [IChartCategory](../../com.aspose.slides/ichartcategory) को खोजता है और पूरी संग्रह में पहली उपस्थिति का शून्य-आधारित अनुक्रमांक लौटाता है। |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | दिए गए अनुक्रमांक पर तत्व को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

**पर्याएँ:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न मान:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - निर्दिष्ट अनुक्रमांक पर तत्व।

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

यदि true हो तो कार्यपत्रक श्रेणियों को संग्रहीत करने के लिये उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)। यदि false हो तो कार्यपत्रक मानों को संग्रहीत करने के लिये उपयोग नहीं किया जाता (और यह मामला बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न मान:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

यदि true हो तो कार्यपत्रक श्रेणियों को संग्रहीत करने के लिये उपयोग किया जाता है (यह मामला बहु-स्तरीय श्रेणियों का समर्थन करता है)। यदि false हो तो कार्यपत्रक मानों को संग्रहीत करने के लिये उपयोग नहीं किया जाता (और यह मामला बहु-स्तरीय श्रेणियों का समर्थन नहीं करता)। पढ़ने/लिखने योग्य बूलियन।

**पर्याएँ:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

उपयोग किए गए श्रेणी समूह स्तरों की गणना लौटाता है। बहु-स्तरीय श्रेणियों के लिये यह एक से अधिक होता है। केवल- पढ़ने योग्य int।

**रिटर्न मान:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

यदि श्रेणी संग्रह में मौजूद है, तो इसे लौटाता है। अन्यथा [IChartDataCell](../../com.aspose.slides/ichartdatacell) से नई चार्ट श्रेणी बनाता है और इसे संग्रह में जोड़ता है।

**पर्याएँ:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | चार्ट श्रेणी बनाने के लिये उपयोग किया जाने वाला सेल। |

**रिटर्न मान:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - जोड़ी गई या मौजूदा श्रेणी।

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

मान से नया [IChartCategory](../../com.aspose.slides/ichartcategory) बनाता है और इसे संग्रह में जोड़ता है।

**पर्याएँ:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object | मान।

--------------------

यह विधि AUTO_DATA नाम के साथ कार्यपत्रक जोड़ती है और सभी मान वहाँ जोड़ती है। यदि आप [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) का उपयोग करके सेल मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्रक का उपयोग न करें। इस विधि द्वारा जोड़े गए मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए।

**रिटर्न मान:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - जोड़ा गया [IChartCategory](../../com.aspose.slides/ichartcategory)।

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

निर्दिष्ट [IChartCategory](../../com.aspose.slides/ichartcategory) को खोजता है और पूरी संग्रह में पहली उपस्थिति का शून्य-आधारित अनुक्रमांक लौटाता है।

**पर्याएँ:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | चार्ट श्रेणी। |

**रिटर्न मान:**
int - यदि पाया जाए तो पूरी CollectionBase में मान की पहली उपस्थिति का शून्य-आधारित अनुक्रमांक; अन्यथा -1।

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

निर्दिष्ट मान को हटाता है।

**पर्याएँ:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | मान। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

दिए गए अनुक्रमांक पर तत्व को हटाता है।

**पर्याएँ:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिये श्रेणी का अनुक्रमांक। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्वों को हटाता है।