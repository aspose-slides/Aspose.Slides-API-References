---
title: ChartCellCollection
second_title: Aspose.Slides for Java API संदर्भ
description: डेटा वाले कोशिकाओं का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/chartcellcollection/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

डेटा वाले कोशिकाओं का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | वर्कबुक में कोशिकाओं के सेट का पता लौटाता है। |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | सभी कोशिकाओं के स्ट्रिंग मानों से संयोजन स्ट्रिंग। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा एक कोशिका (IChartDataCell) लौटाता है। |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | संग्रह में नया कोशिका जोड़ें। |
| [add(Object value)](#add-java.lang.Object-) | [ChartDataCell](../../com.aspose.slides/chartdatacell) को निर्दिष्ट मान से बनाता है और इसे संग्रह में जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | इंडेक्स द्वारा संग्रह से एक कोशिका हटाता है। |
| [getCount()](#getCount--) | संग्रह में कोशिकाओं की संख्या प्राप्त करता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटेरेटर लौटाता है। |
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

सभी कोशिकाओं के स्ट्रिंग मानों से संयोजन स्ट्रिंग।

**रिटर्न:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

इंडेक्स द्वारा एक कोशिका (IChartDataCell) लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कोशिका का इंडेक्स। |

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - डेटा वाली कोशिका।
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

संग्रह में नया कोशिका जोड़ें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | जोड़ने के लिए नई कोशिका। |
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

यह विधि AUTO_DATA नाम की कार्यपत्रिका जोड़ती है और सभी मान वहां जोड़ती है। यदि आप [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) का उपयोग करके Cell मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्रिका का उपयोग न करें। इस विधि का उपयोग करके जोड़े गए मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

इंडेक्स द्वारा संग्रह से एक कोशिका हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए कोशिका का इंडेक्स। |
### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में कोशिकाओं की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

पूरे संग्रह के लिए जावा इटेरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - पूरे संग्रह के लिए java.util.Iterator।
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject