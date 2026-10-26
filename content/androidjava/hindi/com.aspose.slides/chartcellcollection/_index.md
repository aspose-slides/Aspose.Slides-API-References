---
title: ChartCellCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: डेटा वाले कोशिकाओं का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/chartcellcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

डेटा वाले कोशिकाओं का संग्रह प्रस्तुत करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | वर्कबुक में कोशिकाओं के सेट का पता लौटाता है। |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | सभी कोशिकाओं की स्ट्रिंग मानों से संयोजन स्ट्रिंग। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा एक सेल (IChartDataCell) लौटाता है। |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | संग्रह में नया सेल जोड़ता है। |
| [add(Object value)](#add-java.lang.Object-) | [ChartDataCell](../../com.aspose.slides/chartdatacell) को निर्दिष्ट मान से बनाता है और इसे संग्रह में जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | इंडेक्स द्वारा संग्रह से एक सेल हटाता है। |
| [getCount()](#getCount--) | संग्रह में कोशिकाओं की गणना प्राप्त करता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला एक एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

वर्कबुक में कोशिकाओं के सेट का पता लौटाता है।

**रिटर्न:**  
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

सभी कोशिकाओं की स्ट्रिंग मानों से संयोजन स्ट्रिंग।

**रिटर्न:**  
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

इंडेक्स द्वारा एक सेल (IChartDataCell) लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सेल का इंडेक्स। |

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - डेटा के साथ सेल।

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

संग्रह में नया सेल जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | जोड़ने के लिए नया सेल। |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

[ChartDataCell](../../com.aspose.slides/chartdatacell) को निर्दिष्ट मान से बनाता है और इसे संग्रह में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object | मान।  

--------------------

यह विधि AUTO_DATA नाम के साथ कार्यपत्र जोड़ती है और सभी मान वहाँ जोड़ती है। यदि आप [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) का उपयोग सेल मान जोड़ने या संपादित करने के लिए करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्र का उपयोग न करें। इस विधि से जोड़े गए मानों की अधिकतम संख्या 16711680 |  

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

इंडेक्स द्वारा संग्रह से एक सेल हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए सेल का इंडेक्स। |

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में कोशिकाओं की गिनती प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एक एन्यूमरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - एक java.util.Iterator पूरे संग्रह के लिए।

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**  
com.aspose.slides.IDOMObject